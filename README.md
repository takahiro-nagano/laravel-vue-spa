
# 環境
PHP、Composer、NPMが利用可能な環境で  
下記のビルド作業

# ビルド
・PHP側パッケージインストール  
`composer install`

・.env修正  

・DB、テストデータ生成
`php artisan migrate --seed`

・フロントエンドパッケージインストール  
`npm install`

・フロントエンドビルド  
`npm run dev`
