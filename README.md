# Books REST API [GO]

> Under light developenet

A minimal RESTful API to create, read, update and delete books. No database implementation yet
Looking forward to be a full go rest api with Mongo databse intergration.

## Quick Start

```bash
# Install mux router
go get -u github.com/gorilla/mux
go build
./go_restapi
```

## Endpoints

### Get All Books

```
GET api/books
```

### Get Single Book

```
GET api/books/{id}
```

### Delete Book

```
DELETE api/books/{id}
```

### Create Book

```bash
POST api/books

# Request sample
# {
#   "isbn":"4545454",
#   "title":"Book Three",
#   "author":{"firstname":"Harry",  "lastname":"White"}
# }
```

### Update Book

```bash
PUT api/books/{id}

# Request sample
# {
#   "isbn":"4545454",
#   "title":"Updated Title",
#   "author":{"firstname":"Harry",  "lastname":"White"}
# }

```

## Author

Alpha Olomi [hello@alphaolomi.com](mailto:hello@alphaolomi.com)

## Version

0.0.2

## License

This project is licensed under the MIT License
