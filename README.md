# Nextcloud from Docker

### Author: `Marsh Meg`

For run this app:
- Install `Docker`, `nginx 1.15.5+`
- Add include (`./nginx.conf.d`) in nginx.conf
- Create and change `./.env` file

#### Exemple `./.env` file:
```
DB_ROOT_PASSWORD=   # passwort for root user 

DB_USER=            # user for cloud 
DB_PASSWORD=        # password for user 
DB_DATABASE=        # db name

CLOUD_PORT=         # cloud port (DONT SET 80 and 443)
```