<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Products Microservice

## Dev

1. Clonafr repo
2. Instalar dependencias `npm install`
3. Crear un archivo `.env` basado en el `env.template`
4. Ejecutar migracion de prisma `npx prisma migrate dev`
5. Ejecutar `npm run start:dev`



## Nats
```
docker run -d --name nats-server -p 4222:4222 -p 6222:6222 -p 8222:8222 nats
```