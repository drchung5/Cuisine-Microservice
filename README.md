# Cuisine Microservice

Listening on port: 7000

### Get all cuisines
curl --location --request GET 'localhost:7000/cuisines'

### Get a cuisine
curl --location --request GET 'localhost:7000/cuisines/2'

### Add a cuisine
curl --location --request POST 'http://localhost:7000/cuisines' \
--header 'Content-Type: application/json' \
--data-raw '{"cuisine_id":4, "name":"Pho"}'