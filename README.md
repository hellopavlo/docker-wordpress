# Docker Wordpress

## Usage
`docker-compose up -d` - Run the environment.

`docker-compose down` - Stop the environment, keep the volumes.
`docker-compose down -v` - Stop the environment, remove the volumes.

## Generate certs
`sudo openssl req -nodes -newkey rsa:2048 -keyout wpforms-docker.local.key -out wpforms-docker.local.crt -x509 -days 365`