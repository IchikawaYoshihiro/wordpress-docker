# WordPress docker

WordPressテーマ開発用のLAMP開発環境。

# Containers

- App
  wordpress:latest
- DB
  mysql:latest
- Mailhog

# usage

```
git clone https://@github.com/IchikawaYoshihiro/wordpress-docker.git
cd wordpress-docker

docker-compose up
```
srcディレクトリ内にWordPressの全ファイルがマウントされたらlocalhostアクセスして通常のWordPress同様に設定をする。

