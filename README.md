# Fiber Todo API Demo

This is the source code of the demo application that I made for a blog post. It's essentially an intro to [Fiber](https://github.com/gofiber/fiber), an Express-like web framework written in Go.

## Prerequisites

  * Go
  * MongoDB with a database called `todos`

## Getting Started

### Clone the repo

```sh
git clone git@github.com:jozsefsallai/fiber-todo-demo.git
cd fiber-todo-demo
```

### Install the dependencies

```
go mod tidy
```

### Run the app

```
go run server.go
```

### ...or build a binary and run that

```
go build . -o todoapi
./todoapi
```

### Custom connection string

Use the `MONGODB_CONNECTION_STRING` environment variable to specify a custom MongoDB connection string:

```sh
MONGODB_CONNECTION_STRING=mongodb://user:pass@host:27017 go run .
```

## License

MIT.
