# engnr_prof_app

## 開発環境DBのセットアップ
### .envの更新
~~~
DB_CONTAINER_NAME =
DB_ROOT_PASSWORD =
DB_NAME = 
DB_VOLUME =
DB_PORT =
~~~

### colimaのインストール・起動(docker実行環境)
https://github.com/abiosoft/colima
~~~sh
brew install colima
~~~
~~~sh
colima start
~~~

### docker環境の構築
~~~sh
cd ./docker
sh setup.sh
~~~