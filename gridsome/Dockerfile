# 使うイメージ
FROM node:14.5.0-alpine3.11
# 作業場所（初期位置）の指定
# WORKDIR /app
# 実行するコマンド
RUN apk update && \
  # gitをインストール
  apk add git & \
  npm install -g npm && \
  # gridsomeを入れる
  npm install -g @gridsome/cli && \ 
  # gridsomeのStrapiのやつを入れる
  npm install -g @gridsome/source-strapi
