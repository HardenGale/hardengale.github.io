# 1. 安装 Bundler
gem install bundler
gem sources --remove https://rubygems.org/
gem sources --remove https://rubygems.org/

gem sources --add https://gems.ruby-china.com/

# 2. 安装项目依赖 (Jekyll 等)
bundle install

# 3. 构建网站
bundle exec jekyll serve