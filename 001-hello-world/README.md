# What I do

## 1: Create directory 001-hello-world
## 2: Create file by the name hello.go
## 3: In terminal I run `go mod init 001-hello-world/hello`
## 4: In hello.go file code my hello world application
````hello.go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
````
## 5: In terminal run `go run .`
````shell
Hello, World!
````
### Note: Don't forgot put space + dot.

## 6: Also you can use `go run .\hello.go` to run your application.
## 7: To Build executable file you should use `go build .\hello.go` which build .exe file for you.
### Note: I use gitignore to remove hello.exe
