# Zay eCommerce

This is a demo project for Containerization & Linux elective at [UCL University College](https://ucl.dk)

The frontend is based on the following template:

* https://github.com/mosaadaldeen/zay-shop

## Frontend

There is a specific README.md file in the frontend project

## Backend

There is a specific README.md file in the backend project


# Projekt
For at køre projektet skal man lige builde begge images fra dockerfilerne i henholdsvis frontend og backend mapperne:
> docker build -t frontend .        Hvor current directory er frontend

> docker build -t backend .         Hvor current directory er backend

Herefter for at deploye, så skal man køre "docker stack deploy" commanden i projektets mappe:
> docker stack deploy --compose-file docker-compose.yml stacktest
