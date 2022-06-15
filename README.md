# go-tutorial

##  Composite Literal ##
```
package main

import "fmt"

type A struct {
	m, n string
}

func (a *A) display() {
	fmt.Println("TESt")
}

type B struct {
	A
}

func main() {
	a := B{A: A{"k", "j"}}
	a.display()
}
```
