## Opcache Settings

```
opcache.enable=1
opcache.memory_consumption=512
opcache.interned_strings_buffer=64
opcache.max_accelerated_files=20000
opcache.validate_timestamps=0
opcache.save_comments=1
opcache.fast_shutdown=1
```

## Laravel Tips

- Run `config:cache`
- If not using sessions, commented out the middleware in the `web` middleware group of the `app/Http/Kernel.php` file.
