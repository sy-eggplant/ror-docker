# README
## 参考
https://qiita.com/otama/items/9e7d00b4fdd8d647b688

## 起動
docker run -d -p 3000:3000 -v "$PWD":/app otama/rails-app

## コンテナ
docker ps
### 外からコマンドを叩くとき
docker exec -it <コンテナID> rails g controller top index

### コンテナに入るとき
docker exec -it <コンテナ名前> bash

