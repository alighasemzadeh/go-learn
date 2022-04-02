# Comments
Comments line won't compile and run in your application. 
Comments in code is important because make your code more readable and other people understand your codes.

## Single Line Comment
For single line comment use `//`, Like example.
```go
// This is a comment
package main
import ("fmt")

func main() { // This is a comment
  // This is a comment
  fmt.Println("Hello World!")
}
```

## Multi Line Comment
Multi line comment start with `/*` and ends with `*/`.
```go
package main
import ("fmt")

func main() {
  /* Comments line won't compile and run in your application.
  This is multi line comment */
  fmt.Println("Hello World!")
}
```
