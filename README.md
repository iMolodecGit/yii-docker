# YHelper docker

1. Install docker
[Click here](https://www.digitalocean.com/community/tutorials/docker-ubuntu-18-04-1-ru) to see instruction

2. Install docker compose
[Click here](https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-18-04) to see instruction

3. Download the necessary projects and put on the same level with this folder

4. Open docker-compose.yml and press play button

==================

useful commands:

# show all containers 
docker ps   

#up container
docker-compose up [containerName]

# execute an interactive bash shell on the container
docker exec -it ${containerId} bash  
