# Variables

Data stores in variables within name.
This data store in RAM not in HDD, then after program finished memory become free.
Sometimes variable has initiation value and sometimes no, We describe both ways.

## Data Types
Some easy or most used types are:

1. int- stores integers (whole numbers), such as 123 or -123
2. float32- stores floating point numbers, with decimals, such as 19.99 or -19.99
3. string - stores text, such as "Hello World". String values are surrounded by double quotes
4. bool- stores values with two states: true or false

## Define or Create Variable
You can define and create a variable in two ways.

### First: You know type and value
If you know type and value of variable just use bellow code:
```go
var variablename type = value
```

1. `var` is keyword which is brief of variable.
2. `variablename` name of variable.
3. `type` one of data type that I told you in [Data Types](#data-types)
4. `value` is initiation value of variable.

### Second: You don't know type and value
Sometimes you don't know data type and value then just use `:=` to assign value to variable.
```go
variablename := value
```
In this type of variable detonation compiler decide for [Data Types](#data-types).

## Variable with initiation value
To create variable with initiation value you can see bellow example.
```go
package main
import ("fmt")

func main() {
  var name1 string = "Hamed" //type is string
  name2 := "Ali" //type decide by compiler
  grade1 := 2 //type decide by compiler
  var grade2 init = 2 //type is init

  fmt.Println(name1)
  fmt.Println(grade1)
  fmt.Println(name2)
  fmt.Println(grade2)
}
```
Please compile example.