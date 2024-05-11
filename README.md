# hockey

1. run postgres on localhost:5432 with user=postgres, db hockey
2. run application with Program arguments
`--spring.datasource.password=*your password*`

## news
http://localhost:8080/hockey/news **[GET, POST]**
http://localhost:8080/hockey/news/{id} **[GET, PUT, DELETE]**

## teams
http://localhost:8080/hockey/teams **[GET, POST]**
http://localhost:8080/hockey/teams/{id} **[GET, PUT, DELETE]**

## players
http://localhost:8080/hockey/players **[GET, POST]**
http://localhost:8080/hockey/players/{id} **[GET, PUT, DELETE]**

## tournaments
http://localhost:8080/hockey/tournaments **[GET, POST]**
http://localhost:8080/hockey/tournaments/{id} **[GET, PUT, DELETE]**

## coaches
http://localhost:8080/hockey/coaches **[GET, POST]**
http://localhost:8080/hockey/coaches/{id} **[GET, PUT, DELETE]**

## events
http://localhost:8080/hockey/events **[GET, POST]**
http://localhost:8080/hockey/events/{id} **[GET, PUT, DELETE]**

## matches
http://localhost:8080/hockey/matches **[GET, POST]**
http://localhost:8080/hockey/matches/{id} **[GET, PUT, DELETE]**

## results
http://localhost:8080/hockey/results **[GET, POST]**
http://localhost:8080/hockey/results/{id} **[GET, PUT, DELETE]**
