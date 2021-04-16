# letsencrypt-ssl-installation
LetsEncrypt Installation on ec2


sudo certbot certificates

sudo certbot --help

sudo certbot delete

sudo certbot certonly --manual --preferred-challenges dns --server https://acme-v02.api.letsencrypt.org/directory --manual-public-ip-logging-ok -d "*.example.com" -d "example.com"

sudo service apache2 restart 
