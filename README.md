# 帰宅難民注意報

帰宅や帰省の予定を元に、大雪などで帰れなくなってしまう危険性があるときにお知らせします。
(予定)

まずはhttp://spring.io/guides/gs/rest-service/ をgroovyに変換したものからスタート。

## ビルド方法

[gradle]([http://gradle.org]) でGradleラッパー(gradlew)を生成しているため、gradlewコマンドを実行するだけで良い。

### 実行

    ./gradlew bootRun

http://localhost:8080/greeting にアクセスすると挨拶を返す。
nameパラメータを渡すことができる。

### war生成

    ./gradlew war
