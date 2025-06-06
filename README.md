# SNS風MERNアプリ 📱

このプロジェクトは、MERNスタック（MongoDB, Express, React, Node.js）を用いて開発した簡易的なSNSアプリです。ユーザー登録、ログイン、投稿などの基本的な機能を実装しています。

## 🔧 主な機能

- ユーザー登録・ログイン（JWT認証）
- 投稿作成／削除
- 投稿一覧の表示（タイムライン形式）
- フロントエンド：React + Axios
- バックエンド：Express / Node.js
- データベース：MongoDB Atlas

## 💻 使用技術

- Frontend: React, CSS Modules
- Backend: Node.js, Express
- DB: MongoDB (Mongoose)
- 認証: JWT（JSON Web Token）



## 🚀 起動方法

1. `.env` ファイルを作成して、MongoDB URI や JWT_SECRET を記述
2. バックエンド
   ```bash
   cd backend
   npm install
   npm start

