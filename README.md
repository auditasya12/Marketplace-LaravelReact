Hi, salam kenal...nama saya Quin Audi Tasya Effendy, dan akrab dipanggil Quin. Saya seorang developer junior web developer

# SISTEM INFORMASI MARKETPLACE LARAVEL REACT #
bahasa pemrograman :
1. Laravel 8
2. React 16 (npm 10.7.0)


## Instalasi

clone project atau download

```bash
  git clone https://github.com/auditasya12/Sistem-Prestasi-Mahasiswa.git
  cd Marketplace-LaravelReact
### backend 
  cd backend-laravel
  composer install
  cp .env.example .env
### frontend
  cd frontend-react
  npm install

jika error jalankan
  npm install --legacy-peer-deps
  npm install --force
```


Masuk folder backend-laravel (buka `.env` dan atur database anda)
```bash
  DB_PORT=3306
  DB_DATABASE=laravel8-react-ecommerce
  DB_USERNAME=root
  DB_PASSWORD=
```

Install website & database
```bash
  import database .sql didalam folder kedalam database
  php artisan key:generate
```

Jalankan website
```bash
### backend
  masuk folder backend-laravel di terminal lalu jalankan (php artisan serve)
### frontend
  masuk folder frontend-react di terminal lalu jalankan (npm start)
```
