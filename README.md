stratos-docker-php-image
========================

Format of the docker run command with environment variables:

docker run -d -P --name sajith --env SERVICE_NAME=php --env CLUSTER_ID=cluster1.php.stratos.org --env DEPLOYMENT=default --env PORTS=80 --env MEMBER_ID=member1.cluster1.php.stratos.org --env NETWORK_PARTITION_ID=ec2 --env PARTITION_ID=zone-1 --env CARTRIDGE_KEY=NfxZXmklUvRWslG5 --env REPO_URL=null --env TENANT_ID=1  --env MB_IP=10.219.73.77 --env MB_PORT=61616 --env CEP_IP=10.219.73.77 --env CEP_PORT=7611 sajhak/stratos-php
