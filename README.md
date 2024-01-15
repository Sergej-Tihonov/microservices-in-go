# microservices-in-go

# run frontend

navigate to the `front-end` folder

run `go run ./cmd/web` in terminal

open `http://localhost:80` in the browser

# run broker

navigate to the `broker-service` folder

run `go run ./cmd/api` in terminal

# build & run docker compose

navigate to the `project` folder

to run docker instance in the background:
```
docker compose up -d
```

to enter the terminal of the docker instance:
```
docker compose exec broker-service ash
```

to stop docker instance:
```
docker compose stop
```
