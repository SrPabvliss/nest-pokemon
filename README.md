<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1.  Clonar el repositorio
2.  Ejecutar

```
yarn install
```

3.  Tener Nest CLI instalado

```
npm i -g @nestjs/cli
```

4.  Levantar la base de datos

```
docker-compose up -d
```

5. Clonar el archivo `env.template` y renombrar a `.env`

6. Llenar las variables de entorno definida en ```.env```

7. Ejecutar la aplicació en modo de desarrollo

```
yarn start:dev
```

8. Obtener data de una seed

```
localhost:3000/api/v2/seed
```

>La aplicación ha sido deployada en los siguientes dominios:  
Nestjs app : https://nest-pokemon-production-c43b.up.railway.app/  
MongoDB: mongodb://mongo:CddB43gDAh-b6Fgag6fbgBcDe-3-BcEC@monorail.proxy.rlwy.net:48695

## Stack usado

- MongoDB
- Nest
