source "https://rubygems.org"

ruby "3.2.2"

# エッジRailsをバンドルする代わりに: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.7", ">= 7.0.7.2"

# Railsのオリジナルのアセットパイプライン [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Active Recordのデータベースとしてsqlite3を使用する
gem "mysql2"

# Pumaウェブサーバーを使用する [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# ESMインポートマップでJavaScriptを使用する [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# HotwireのSPA風ページアクセラレータ [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwireの控えめなJavaScriptフレームワーク [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# JSON APIを簡単に構築する [https://github.com/rails/jbuilder]
gem "jbuilder"

# 本番環境でAction Cableを実行するためのRedisアダプターを使用する
# gem "redis", "~> 4.0"

# Redisで高レベルのデータタイプを取得するためのKredisを使用する [https://github.com/rails/kredis]
# gem "kredis"

# Active Model has_secure_passwordを使用する [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windowsにはzoneinfoファイルが含まれていないため、tzinfo-data gemをバンドルする
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# キャッシングを通じて起動時間を短縮する; config/boot.rbで必要
gem "bootsnap", require: false

# CSSを処理するためにSassを使用する
# gem "sassc-rails"

# Active Storage variantsを使用する [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gemを参照してください
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

# deviseを使用できる
  gem 'devise'
 
  # bootstrapを使用できる
  gem 'bootstrap', '~> 4.6.0'
  gem 'jquery-rails'


group :development do
  # 例外ページでコンソールを使用する [https://github.com/rails/web-console]
  gem "web-console"

  # スピードバッジを追加する [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  # 遅いマシン/大規模なアプリでコマンドをスピードアップする [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # システムテストを使用する [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

