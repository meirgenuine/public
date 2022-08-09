# BinaryCheck

### Instructions

Write a function called `BinaryCheck()` that takes an integer in parameter and return 0 if the number is odd and 1 if the number is even.

### Expected function

```go
func BinaryCheck(nbr int) int {
}
```

### Usage

Here is a possible program to test your function:

```go
package main

func main() {
    fmt.Println(BinaryCheck(5))
    fmt.Println(BinaryCheck(0))
    fmt.Println(BinaryCheck(8))
    fmt.Println(BinaryCheck(-9))
    fmt.Println(BinaryCheck(-4))

}
```

And its output :

```go
$ go run .
0
1
1
0
1
```
