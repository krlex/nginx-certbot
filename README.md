# docker-compose nginx certbot

## Fast install docker
Start script

`./fast-install.sh`

Edit `nginx/conf/nginx.conf`
Change `krletron.ml` to your `domain-name.com` and
also path of your `/var/www/certbot`
after that do:

`docker-compose up -d`
