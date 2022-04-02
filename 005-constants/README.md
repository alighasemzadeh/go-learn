# Constants

Constants are variables which you can't change value of them.
You can define constant value like bellow:
```go
const CONSTNAME type = value
```

You use data_type or not, but you can't change value.
Good example of constants is `PI=3.14`
```go
package main
import ("fmt")

const PI = 3.14

func main() {
  fmt.Println(PI)
}
```

You can define multiple constants in a block.
```go
const (
  A int = 1
  B = 3.14
  C = "Hi!"
)
```