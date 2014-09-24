stratos-docker-php-image
========================

Download Java
-------------
Go to packs directory

wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/7u4-b20/jdk-7u4-linux-x64.tar.gz"

Download ActiveMQ
-----------------
Go to packs/activemq directory

wget http://www.carfab.com/apachesoftware/activemq/5.9.1/apache-activemq-5.9.1-bin.tar.gz


Download cartridge agent to packs directory

Start a container
----------------
Format of the docker run command with environment variables:

docker run -d -P --name sajith --env SERVICE_NAME=php --env CLUSTER_ID=cluster1.php.stratos.org --env DEPLOYMENT=default --env PORTS=80 --env MEMBER_ID=member1.cluster1.php.stratos.org --env NETWORK_PARTITION_ID=ec2 --env PARTITION_ID=zone-1 --env CARTRIDGE_KEY=NfxZXmklUvRWslG5 --env REPO_URL=null --env TENANT_ID=1  --env MB_IP=10.219.73.77 --env MB_PORT=61616 --env CEP_IP=10.219.73.77 --env CEP_PORT=7611 sajhak/stratos-php
