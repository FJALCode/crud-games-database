# CRUD Games-database

Database de la APP de Games, realizado con PostgreSQL y pg-promise, en este proyecto encontraremos una BD de ejemplo con datos para usar como ejemplo

## Pre-requisitos

Para este proyecto se utilizarón las siguientes herramientas

* [PostgreSQL](https://www.postgresql.org/)
* [Pg-promise](https://www.npmjs.com/package/pg-promise)

## Instalación
1. Dentro de pgAdmin elegimos nuestra BD y damos click derecho en `restore`

2. Damos click en `filename`, elegimos la base de datos y luego damos click en `restore`

##### Opcional
En caso de querer utilizar nuestros propios datos, podemos crear la BD y tabla con los siguientes scripts
```bash
CREATE DATABASE ng_games_db
```
```bash
CREATE TABLE games
(
    id SERIAL,
    title character varying(180),
    description character varying(255),
    image character varying,
    created_at timestamp with time zone DEFAULT CURRENT_TIMESTAMP,
    PRIMARY KEY (id)
)
```


## Version

1.0.0

## Autores

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
[<img src="https://avatars2.githubusercontent.com/u/48934580?s=460&v=4" width="100px;"/><br /><sub><b>Fernando Antúnez</b></sub>](https://github.com/FJALCode)<br />[💻](https://github.com/FJALCode "Code") [📢](#talk-Meabed "Talks")
<!-- ALL-CONTRIBUTORS-LIST:END -->

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE)

## Expresiones de Gratitud
Este proyecto se realizo gracias al trabajo base de: 
</br>[<img src="https://avatars3.githubusercontent.com/u/13667358?s=460&v=4" width="100px;"/><br/><sub><b>Fazt</b></sub>](https://github.com/FaztTech)


