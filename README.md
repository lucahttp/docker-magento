# docker magento


https://hub.docker.com/r/bitnami/magento/


wget https://raw.githubusercontent.com/bitnami/bitnami-docker-magento/master/docker-compose.yml -O docker-compose.yml

docker-compose up -d


<VirtualHost *:80>
	DocumentRoot "C:/xampp/htdocs/"
	ServerName localhost
</VirtualHost>


<VirtualHost *:80>
    ServerAdmin webmaster@lukaneco.ga
    DocumentRoot "C:/xampp/htdocs/lukaneco.ga"
    ServerName lukaneco.ga
    ServerAlias www.lukaneco.ga
    ErrorLog "logs/lukaneco.ga-error.log"
    CustomLog "logs/lukaneco.ga-access.log" common
</VirtualHost>

