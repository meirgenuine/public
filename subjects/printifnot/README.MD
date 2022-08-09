# printifnot

### Instructions

Create a function  `PrintIfNot()` that takes a string in the parameter and return `G` followed by a newline if the argument length is less than 3; otherwise, return "Invalid Output\n".

- If it's an empty string return `G` followed by a newline.

### Expected function

```go
func PrintIfNot(str string) string {
}
```

### Usage

Here is a possible program to test your function:

```go
package main

import (
	"fmt"
)

func main() {
    fmt.Print(PrintIfNot("abcdefz"))
    fmt.Print(PrintIfNot("T2d97d1"))
    fmt.Print(PrintIfNot(""))
    fmt.Print(PrintIfNot("14"))
}
```

And its output :

```go
$ go run . | cat -e
Invalid Output$
Invalid Output$
G$
G$
```
