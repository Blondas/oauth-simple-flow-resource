# 1. Create a library
```shell
curl -X POST http://localhost:8080/libraries \
-H "Content-Type: application/json" \
-d '{"name":"City Lib","city":"Zurich"}'
```

# 2. Create a book in library id=1
```shell
curl -X POST http://localhost:8080/books \
-H "Content-Type: application/json" \
-d '{"title":"Clean Code","author":"Martin","library":{"id":1}}'
```

# 3. Add a review for book id=1
```shell
curl -X POST http://localhost:8080/reviews \
-H "Content-Type: application/json" \
-d '{"content":"Great read","rating":5,"book":{"id":1}}'
```

#4. Get library:
```shell
curl -X GET http://localhost:8080/libraries \
-H "Content-Type: application/json" 
```