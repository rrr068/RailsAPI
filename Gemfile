source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# railsの起動時間を短縮する（標準gem）
gem "bootsnap", require: false

# MySQLに接続する
gem "mysql2", "~> 0.5"

# pumaサーバーを使えるようにする（標準gem）
gem "puma", "~> 5.0"

# レスポンスJSONを制御する
gem "active_model_serializers"

# メッセージを日本語化
gem "rails-i18n"

# cors設定を管理する
gem "rack-cors"

# 環境毎の設定管理を行う
gem "config"

# ユーザー認証を提供する
gem "devise"

# devise を日本語化する
gem "devise-i18n"

# ユーザーのトークン認証を提供する
gem "devise_token_auth"

# enum を日本語化する
gem "enum_help"

# ページネーション機能を提供する
gem "kaminari"

# N+1発生時にアラートを表示する
gem "bullet"

# rails本体（標準gem）
gem "rails", "~> 7.0.4"

# タイムゾーン情報を提供する（標準gem）
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do

  # 開発環境でメール送信をテストする
  gem "letter_opener_web"

end