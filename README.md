# Docker Vue-cli 3

> Docker-compose for @vue/cli (NODE - VUE3)

Build and run container

```sh
$ docker-compose build
$ docker-compose up -d
```

Create a new `vue/cli` webpack proyect

```sh
$ docker-compose run --rm vue bash
$$ vue init webpack . 
```

Run dev

```sh
$ docker-compose run --rm vue bash
$$ npm run dev
```

Access project

```sh
http://localhost:8080
```