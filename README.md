# Hi there, I'm Gabriel! 👋

```go
package main

import "fmt"

type Student struct {
  Name       string
  University string
  Major      string
  Stack      []string
  OS         string
}

func main() {
  gabriel := Student{
    Name:       "Gabriel",
    University: "Universidade Estadual de Goiás (UEG)",
    Major:      "Sistemas de Informação",
    Stack:      []string{"Go", "C++", "Java", "C"},
    OS:         "Arch Linux",
  }

  fmt.Printf("%+v\n", gabriel)
}
