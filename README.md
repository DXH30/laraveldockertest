# Cara pake nya ?
Copy itu docker-compose.yaml sama Dockerfile ke gitmu\\
Copy semua file app laravel nya ke src\\
Terus\\

```
docker-compose up -d
```

Untuk Migrate caranya
```
docker-compose exec php php /var/www/html/artisan migrate:fresh
```
