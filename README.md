# Simple Web Server in Go

This is a simple web server written in Go. It serves a static HTML file and a JSON API.

## Running the server

First, you have to install Go. You can download it from the [official website](https://golang.org/).

Setup the Go module with the following command. Make sure that you are in the root directory of the project:

```bash
go mod init golang-web-server
```

Build the Go executable with the following command:

```bash
go build
```

To run the server, execute the following command:

```bash
go run main.go
```

The server has three routes:
1. `/`: This is the default route which serves the static page.
2. `/hello`: This displays 'hello' on the screen.
3. `/form`: This displays a page where the user is prompted for their name and address. This data is then printed on the screen.
