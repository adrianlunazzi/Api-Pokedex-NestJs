<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en Desarrollo

1. Clonar el repositorio
2. Ejecutar el comando 
```
yarn install
```
3. Tener nest CLI instalado
```
npm i -g @nestjs/cli
```
4. Levantar la base de datos
```
docker-compose up -d
```
5. Clonar el archivo __.env.template__ y renombrar la copia a __.env__

6. Completar las variables de entorno definidas en el __.env__

7. Iniciar aplicacion
```
yarn start:dev
```

6. Poblar la base de datos mediante un seeder
```
http://localhost:3000/api/v2/seed
```
## Stack de desarrollo
- NestJs
- Mongo Db

