<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>


# Run in dev
1. Clone repo
2. Execute
  ```
  yarn install
  ```
3. Install Nst CLI
  ```
  npm i -g @nestjs/cli
  ````
4. Setup DB
```
  docker-compose up -d
```
5. Clonar el archivo __.env.template__ y renombrar la copia a __.env__
6. Llenar las variables de entorno definidas en el  __.env__
7. Ejecutar la aplicacion en dev:
  ```
  yarn start:dev
  ```
8. Seed data base
  ```
  http://localhost:3000/api/v1/seed
  ```


## Stack
* MongoDB
* Nestjs