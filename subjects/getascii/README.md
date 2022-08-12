### getascii

### Instructions

Write a program that takes a character as an argument, and displays its ASCII followed by a newline.

If the Inputs is more than one character , returns a newline.
If the number of arguments is less than 1, returns a newline.
If the number of arguments is more than 1, returns a newline.

### Usage

$ go run . "W" | cat -e
87$
$ go run . ">" | cat -e
62$
$ go run . "^" | cat -e
94$
$ go run . 7 | cat -e
55$
$ go run . a | cat -e
101$
$ go run . "Stay Home!" | cat -e
$
$ go run .
$