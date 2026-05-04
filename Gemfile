source "https://rubygems.org"

# 1. 核心 Jekyll 引擎
gem "jekyll", "~> 4.4.1"

# 2. 插件组：这里放所有主题和插件
group :jekyll_plugins do
  # Cayman 主题（用于 GitHub Pages 的开源主题）
  gem "jekyll-theme-cayman"
  
  # Cayman 是远程主题，必须安装此插件才能加载
  gem "jekyll-remote-theme"
  
  # RSS 订阅插件（通常需要）
  gem "jekyll-feed", "~> 0.12"
end

# 3. Windows 兼容性设置（保留你原有的，无需改动）
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# 4. Windows 目录监听性能优化
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]