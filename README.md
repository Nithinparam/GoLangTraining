#   GoLang Training



##  Why Go 
*   Efficient Compilation
*   Efficient Execution
*   Ease of Programming
---
##  Go Commands
```Go
go version
go env
go help
go fmt
go get
go run filename.go
go build
go install
go test
```
----

## Hello World
```Go
package main

import (
	"fmt"
)

func main() {
	fmt.Println("Hello,World")
}
```
### func main
*   is the entry point to program
* when code exits func main, the program is over


##  Keywords
```Go
break       default         func        interface       select

case        defer           go          map             struct

chan        else            goto        package         switch

const       fallthrough     if          range           type

continue    for             import      return          var
```

## Variables , Values & Types

### Numbers
*   ###   Integers
```
    --  uint8   uint16      uint32      uint64
    --  int8    int16       int32       int64
    --  byte    <--     same as int8
    --  rune    <--     same as int32
```
*   ###     Floating
```
    --  float32         float64
    --  complex32       complex64
```

### Strings