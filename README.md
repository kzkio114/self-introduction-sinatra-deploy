# 自己紹介アプリ

[![Image from Gyazo](https://i.gyazo.com/76a81e8ee1daa0dc2cb4ecfad00fe542.png)](https://gyazo.com/76a81e8ee1daa0dc2cb4ecfad00fe542)

## 概要
完全オンラインのプログラミングスクールにおいて、受講生同士の交流をより活発にするために、自己紹介アプリを作成しました。多くの受講生に利用され、現状を把握するとともに、アプリ開発の楽しさを実感できた良い経験となりました。

## 工夫点
- **動的プロファイル表示**
ユーザーが入力した内容をリアルタイムでプロファイルに反映し、シンプルなインターフェースを実現しました。直感的な操作ができるよう配慮し、快適なユーザー体験を提供しています。

- **柔軟なハッシュ構造**
各質問に応じて詳細情報を動的に表示できるよう、柔軟なハッシュ構造を採用し、効率的な動作を実現しています。

## 技術スタック

| カテゴリー | 使用技術 |
| --- | --- |
| **サーバーサイド** | Ruby (rbenv経由), Sinatra |
| **フロントエンド** | HTML |
| **パッケージ管理** | Homebrew (依存パッケージ用) |
| **デプロイ環境** | Heroku |

## 環境構築方法
### 1. Homebrewのインストール

- [ ] /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### 2. rbenvのインストール

- [ ] brew install rbenv
- [ ] rbenv init

### 3. シェル設定ファイル（`.zshrc`または`.bash_profile`）に以下を追加し、rbenvを有効化します。

- [ ] eval "$(rbenv init -)"

### 4. 指定したRubyバージョンをインストールします。

- [ ] rbenv install 2.x.x
- [ ] rbenv global 2.x.x

### 3. 必要なGemのインストール

- [ ] gem install bundler
- [ ] bundle install

### 4. アプリの起動

- [ ] ruby app.rb

・[http://localhost:4567](http://localhost:4567) にアクセスし、アプリケーションが正しく動作していることを確認してください。
