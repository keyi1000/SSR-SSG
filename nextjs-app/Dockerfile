FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3000

# 開発環境なので dev コマンドを使用
CMD ["npm", "run", "dev"]