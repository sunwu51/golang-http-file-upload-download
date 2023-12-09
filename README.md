# golang-http-file-upload-download

 A simple example of an HTTP upload and download in Go 

 Start with source code ↓
 ```bash
 $ go run main.go
 
 or specify the port number
 
 $ go run main.go 8080
 ```
 Or the binary file in release
 ```bash
 $ ./http_file_server
 
  or specify the port number

 $ ./http_file_server 8080
 ```
# build
```bash
$ CGO_ENABLED=0 GOOS=linux GOARCH=amd64 go build -o linux_amd64/http_file_server main.go
$ CGO_ENABLED=0 GOOS=windows GOARCH=amd64 go build -o win_amd64/http_file_server main.go
$ CGO_ENABLED=0 GOOS=darwin GOARCH=amd64 go build -o darwin_amd64/http_file_server main.go
$ CGO_ENABLED=0 GOOS=darwin GOARCH=arm64 go build -o darwin_arm64/http_file_server main.go
```