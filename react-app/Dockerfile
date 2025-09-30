FROM node:18-alpine

WORKDIR /app

# package.json をコピーして依存関係をインストール
COPY package*.json ./
RUN npm install

# アプリケーションファイルをコピー
COPY . .

# ポートを公開
EXPOSE 3000

# 開発サーバーを起動
CMD ["npm", "start"]