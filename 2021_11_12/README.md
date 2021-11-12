# Clone

```
git clone git@github.com:Kotaro666-dev/development_team.git
```
# Prepare

## .env.sampleの編集

以下の"xxxx"となっている箇所に適当なものを入力してください

```
# MYSQL SETUP
MYSQL_ROOT_PASSWORD=xxxxxxxx
MYSQL_DATABASE=xxxxxxx
MYSQL_USER=xxxxx
MYSQL_PASSWORD=xxxxxx
```

そして、ファイル名を `.env` に変更してください

```bash
$ mv .env.sample .env
```

# Get started

```bash
$ docker compose build
$ docker compose up -d
```
