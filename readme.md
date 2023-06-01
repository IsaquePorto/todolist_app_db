# Banco de dados da aplicação

Esse é o banco de dados do todolist app

## Costruindo a imagem

```
docker build . -t todolistdb
```

## Executando container 

docker run -p 3306:3306 -e MYSQL_ROOT_PASSWORD=senha -d todolistdb
