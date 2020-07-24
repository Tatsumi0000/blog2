# 使うイメージ
FROM node:14.5.0
# 作業場所（初期位置）の指定
WORKDIR /app
# 実行するコマンド
RUN apt-get update && \
  # gitをインストール
  apt-get install git && \
  npm install -g npm && \
  # strapiを入れる
  npm install -g strapi
