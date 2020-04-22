# イメージの元になるイメージ
FROM docker/whalesay:latest

# image buildの際に実行するコマンド。
# docker/whalesayはUbuntuのイメージがベースの為、apt-getコマンドが使用可
RUN apt-get -y update && apt-get install -y fortunes

# コンテナ作成後に実行されるコマンドを指定する
CMD /usr/games/fortune | cowsay