### Http requests
curl -i -X POST -H "Content-Type: application/json" -d '{"name": "BMW"}' localhost:8080/api/makes

curl -i -X PUT -H "Content-Type: application/json" -d '{"name": "Audi"}' localhost:8080/api/makes/3

curl -i -X GET -H "Content-Type: application/json" localhost:8080/api/makes