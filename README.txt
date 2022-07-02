○node.jsのイメージ作成
docker-compose build

○react-appをインストール
docker-compose run --rm node sh -c "npm install -g create-react-app && create-react-app reactapp"

○コンテナ起動
docker-compose up
→2回目以降はこれだけでOK