# ruby-on-rails-docker-compose

## 環境構築手順

### 手順
1. DockerをPCにインストール
2. git clone
3. cd プロジェクトパス
4. docker network create rails_network
5. docker-compose run rails rake db:create
6. docker-compose up -d
7. 落とすときは docker-compose down


### 接続確認
mysql -h 127.0.0.1 -P 3306 -u root -p でmysqlをcliで接続(PW:root)  
localhost:3000 へブラウザでアクセス  

今後色々触って追加していこうと思います
