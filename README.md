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



#docker build --pull --rm -f "1.dockerfile" -t csvtodockermysql:latest "."
#docker run -i -t -d --name mysql_container csvtodockermysql:latest



#docker inspect --format '{{ .NetworkSettings.IPAddress }}' mysql_container

#docker build -t mysql_image .
#docker run -i -t -d --name mysql_container mysql_image


https://pepipost.com/tutorials/how-to-install-magento-on-ubuntu-18-04/

https://account.magento.com/apiportal/index/index/

https://riptutorial.com/es/magento2/example/25231/instale-magento-2-en-ubuntu-16-04

https://tecadmin.net/install-magento2-using-composer-ubuntu/


https://lukaneco.github.io/Script-bash-to-Dockerfile/




magento composer install ubuntu