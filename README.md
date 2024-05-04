# Chirper Laravel 11 Demo 

## Architecture

SendChirpCreatedNotifications (listener) LISTEN TO ChirpCreated (event) TO SEND NewChirp (notification)

## Run

### Event Queue

```
php artisan queue:work
```

## References

https://bootcamp.laravel.com/blade/installation