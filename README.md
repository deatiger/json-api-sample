## LICENSE
The source code is licensed MIT.

## Summary
This is the sample repository to test the request and the response of a simple json api server.   

## Methods
### GET
`curl -X GET "http://localhost:3000/episodes" -v`

### POST
`curl -X POST -H "Content-Type: application/json" -d '{"id": 4, "title": "ロズワール邸の団欒"}' "http://localhost:3000/episodes" -v`

### PUT 
`curl -X PUT -H "Content-Type: application/json" -d '{"id": 4, "title": "ロズワール邸の争乱"}' "http://localhost:3000/episodes/4" -v`

### DELETE
`curl -X DELETE "http://localhost:3000/episodes/4" -v`

### HEAD
`curl -X HEAD "http://localhost:3000/episodes" -v`

### OPTIONS 
`curl -X OPTIONS "http://localhost:3000/episodes" -v`