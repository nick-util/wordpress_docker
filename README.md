## Useful commands

### Start the site with messages
`sudo docker-compose up`

### Start the site silently and detach
`sudo docker-compose up -d`

### Enter inside the container
`sudo docker exec -it <container-name> /bin/bash`

### See all active containers
`sudo docker ps`

### See all containers active or not
`sudo docker ps -a`

### Delete a container
`sudo docker rm <container names>`

### Delete the database and force a fresh wordpress install
`sudo rm -rf /data/db/*`

