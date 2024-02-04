お問い合わせフォーム


Docker ビルド
  git@github.com:keigo-Aoki/coachtest.git
  docker-compose up -d build

Laravel環境構築
  1.docker-compose exec php bash
  2.composer install
  3.
  4.php artisan keygenerate
  5.php artisan migrate
  6.pgp artisan db:seed
  
#使用技術
  laravel  10.43.0
  PHP      8.3.2
  Mysql    8.0.26


URL
  開発環境　　　http://localhost/
  phpMyAdmin  http://localhost:8080/
