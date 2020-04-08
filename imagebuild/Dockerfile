# イメージの元になるイメージ
FROM docker/whalesay:latest

# image buildのの際に実行するコマンド
RUN apt-get -y update && apt-get install -y fortunes

# コンテナ作成後に実行されるコマンドを指定する
CMD /usr/games/fortune | cowsay