# dozzle  
**https://dozzle.dev/**

## Run it docker-compose 
```shell
git cloen https://github.com/Luismcplopes/dozzle.git
cd dozzle
docker-compose up -d
```

## docker run
```shell
docker run --name dozzle -v /var/run/docker.sock:/var/run/docker.sock -p 8383:8080 amir20/dozzle:latest
```

