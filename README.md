<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Dev

1. Clone repository.
2. Execute.

```
yarn install
```

3. Install nest cli.
```
npm i -g @nestjs/cli
```

4. Build database.
```
docker-compose up -d
```
5. Clone the file __.env.template__, and update __.env__ file.

6. Define enviroment variables in ```.env```.

7. Exec app in dev mode. 
```
yarn start:dev
```

8. Populate data with seed.
```
http://localhost:3000/api/v2/seed
```

### Stack
* MongoDB
* NestJS

