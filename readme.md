# Docker: Creating and managing containers


Project developed with contents covered in the course: [Docker: criando e gerenciando containers](https://www.alura.com.br/curso-online-docker-criando-gerenciando-containers?gclid=EAIaIQobChMIi4D-7bLF_QIVwehcCh0AbQDOEAAYASAAEgJ1nvD_BwE)

# Installation

You need to write the following commands on the terminal screen so that you can run the project locally.

```sh
1. git clone git@github.com:mtheusbrito/docker-creating-and-managing-containers.git
2. cd docker-creating-and-managing-containers
3. npm install
4. npm start
```

The application is running on [localhost](http://localhost:3000).



# Containerizing with docker
- current-version: 1.1

```sh 
docker build -t mtheusbrito/app-node:1.1 .
```

### Run

```sh
docker run -d -p 80:3333 mtheusbrito/app-node:1.1

```


### Publish in docker-hub 
```sh
docker push mtheusbrito/app-node:1.1
```


[View in Docker Hub Repository](https://hub.docker.com/r/mtheusbrito/app-node)

