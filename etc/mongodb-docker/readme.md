# Execució amb docker compose

Per crear l'estructura de contenidors i executar-lo
```
docker-compose up -d 
```

Per aturar l'execució
```
docker-compose stop
```

Por tornar-la a arrencar
```
docker-compose start
```

Per eliminar-lo
```
docker-compose down
docker-compose down -v
```


# Administració a través de web-ui
http://127.0.0.1:8081/

usuari: admin
contrasenya: pass


ssh -i .ssh/id_rsa -p 20127 -L 27017:localhost:27017-L 8081:localhost:8081 roscodrom4@ieticloudpro.ieti.cat