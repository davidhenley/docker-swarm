## Run the image at `http://localhost:4000`

`docker run -p 4000:80 friendlyhello`

## Run in detached mode

`docker run -d -p 4000:80 friendlyhello`

## Pull from Docker Hub on any machine

`docker run -p 4000:80 henleydr/get-started:part2`

## Build swarm

1. `docker swarm init`
2. `docker stack deploy -c docker-compose.yml getstartedlab`

## Take down swarm

1. `docker stack rm getstartedlab`
1. `docker swarm leave --force`
