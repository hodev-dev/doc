# install Inercia js + react + ssr + Vite + tailwind 

```
laravel new project
cd project
composer require laravel/breeze --dev
php artisan breeze:install react --ssr
npm install && npm run build
node bootstrap/ssr/ssr.mjs
```
to run server
```
php artisan serve
```

**for hot reload**
```
npm run dev
```