# Wordpress stack

Based on article by [@nawazdhandala](https://github.com/nawazdhandala)

[How to Run WordPress with Docker Compose (Nginx + MySQL + PHP)](https://oneuptime.com/blog/post/2026-02-08-how-to-run-wordpress-with-docker-compose-nginx-mysql-php/view)

Start with:
`docker compose up`

Stop with:
`docker compose down`

## Variables that must be set:


#### [.env](.env)
```
MYSQL_ROOT_PASSWORD=

WordPress security keys (generate at https://api.wordpress.org/secret-key/1.1/salt/)
WP_AUTH_KEY=
WP_SECURE_AUTH_KEY=
WP_LOGGED_IN_KEY=
WP_NONCE_KEY=_Pzh=
WP_AUTH_SALT=
WP_SECURE_AUTH_SALT=
WP_LOGGED_IN_SALT=
WP_NONCE_SALT=
```

#### [ngnix/defaults.conf](ngnix/defaults.conf)

```
server_name yourdomain.com www.yourdomain.com;
```

## TODO:
- Add SSL

