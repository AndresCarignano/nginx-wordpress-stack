## Variables that must be set:

MYSQL_ROOT_PASSWORD=


#### .env
WordPress security keys (generate at https://api.wordpress.org/secret-key/1.1/salt/)
WP_AUTH_KEY=
WP_SECURE_AUTH_KEY=
WP_LOGGED_IN_KEY=
WP_NONCE_KEY=_Pzh=
WP_AUTH_SALT=
WP_SECURE_AUTH_SALT=
WP_LOGGED_IN_SALT=
WP_NONCE_SALT=


#### ngnix/defaults.conf
server_name yourdomain.com www.yourdomain.com;
