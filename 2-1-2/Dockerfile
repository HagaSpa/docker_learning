# ベースのdockerイメージを指定する
FROM golang:1.9

# イメージビルド時にコンテナ内で実行するコマンド
RUN mkdir /echo
# ホストOSから、コンテナ内にファイルをコピーするコマンド
COPY main.go /echo
# コンテナ起動時に実行するプロセス。$go run /echo/main.go と同じ
CMD [ "go", "run", "/echo/main.go" ]