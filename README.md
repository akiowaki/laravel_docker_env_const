# laravel_docker_env_const
ドッカー内でLaravel DB構築の例
- PHP8・Laravel8・mysql・Nginx・docker・phpdebug3
- 参考ブログ記事
　https://maasaablog.com/development/laravel/docker/

ダウンロードしたらdocker-compose.ymlファイルがあるディレクトリと同じ階層でbuildコマンドを実行します。

docker-compose build

キャッシュがあればそちらを優先的に使ってビルドするので、Dockerfileを更新したなどの理由でキャッシュを使いたくない場合は docker-compose build –no-cache とする必要があります

Dockerコンテナを起動

docker-compose up -d

