
# Configuración de Docker para la API de Vacunas

**Requisitos Previos** Asegúrate de tener Docker y Docker Compose instalados en tu máquina. Puedes descargarlos desde [el sitio web oficial de Docker](https://www.docker.com/get-started).

## Contenedores de Docker

- Para **iniciar los contenedores** de Docker para la API de Vacunas, sigue estos pasos

1. Navega al directorio del proyecto donde se encuentra el archivo `docker-compose.yml`
    ``` bash
    cd ruta/a/vaccines-API
    ```
   
2. Ejecuta el siguiente comando para iniciar los contenedores en modo desprendido

    ``` bash
    docker-compose up -d
    ```

3. Verifica que los contenedores estén en ejecución

    ``` bash
    docker ps
    ```
    
- **Detener los Contenedores** de Docker Para detener los contenedores de Docker sin eliminarlos

   ```bash
   docker-compose stop
   ```

- **Eliminar los Contenedores** junto con los volúmenes, puedes hacerlo con el siguiente comando

   ```bash
   docker-compose down
   ```

- **Reiniciar los Contenedores**

   ```bash
   docker-compose start
   ```


## Project setup

```bash
$ npm install
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
