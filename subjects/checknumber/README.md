## checknumber

### Instructions

Write a function that takes a `string` as an argument and returns `true` if the string contains any number, otherwise return `false`.

### Expected function

```go
func CheckNumber(arg string) bool {

}
```

### Usage

Here is a possible program to test your function:

```go
package main

import (
	"fmt"

	"piscine"
)

func main() {
	test := []string{"Hello", "Hello1"}
	fmt.Println(piscine.CheckNumber(test))
}
```

And its output:

```console
$ go run . "Hello"
false
$

$ go run . "Hello1"
true
$
```
