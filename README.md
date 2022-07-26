# Docker project

## Instructions

Services:
- REDIS
- NEXTCLOUD 
- MARIADB
- REVERSE PROXY (traefik, nginx, caddy, apache..)
- HTTPS: certbot or autosigned 

Official nextcloud image: max 15/20
Own nextcloud image: max 20/20

### Php configuration

**/etc/php/7.4/apache2/php.ini**
```
memory limit 1024
upload_max_filesizes = 2048M
```
