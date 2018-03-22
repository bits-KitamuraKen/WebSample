source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# bootstrap
gem 'bootstrap-sass'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # 静的解析ツール
  # -使い方-
  # アプリケーションルートに「.rubocop.yml」を作成し、コーディングルールを設定する
  # 「bundle exec rubocop」を実行する
  gem 'robocop'

  # Gemfile.lockのgemバージョンを調べてセキュリティ問題をチェックする
  # -使い方-
  # プロジェクトのルートディレクトリで「bundle exec bundle-audit」を実行する
  gem 'bundler-audit'

  # 開発中にリクエストの所要時間などをブラウザ画面の隅に表示できる。クリックすると詳細が表示される
  # -使い方-
  # インストールした環境でブラウザを開くだけ
  gem 'rack-mini-profiler'

  # エラー時にリッチなデバッグ画面を表示する
  gem 'better_errors'

  # デバッグ画面でコードや変数の値を変更することもできる
  gem 'binding_of_caller'

  # n+1 問題を検出できる
  gem 'bullet'

  # ソースファイルを整形してくれる
  # -使い方-
  # rufo ファイル名
  gem 'rufo'

  # モデルファイルにテーブルのストラクチャ情報を追記する
  # -使い方-
  # 「bundle exec annotate」を実行する
  gem 'annotate'

  # デプロイ用
  gem 'capistrano'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano3-puma'
  gem 'capistrano-nginx'
  gem 'capistrano-sidekiq'

end

