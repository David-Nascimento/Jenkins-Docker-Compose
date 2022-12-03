# Jenkins para CI

### Subir o container 
```sh
$ docker-compose up -d
```

### Visualizar o log para criar a senha administration
```sh
$ docker logs jenkins | less
```

### Adicionar Jenkins Agent com Dockker Compose
```sh
$ ssh-keygen -t rsa -f jenkins_agent
```
***Adicionar a chave publica no compose***

### Derrubar os containers
```sh
$ docker-compose down
```

### Startar novamente os containers
```sh
$ docker-compose up -d
```