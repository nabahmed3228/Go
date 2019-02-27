Day 01
------

- Goroutines: `go` keyword
- `go build` & `go run` commands
- Syntax
  - Variables, packages and functions
    - Multiple returns, named returns, zero values, type conversion & inference
    - constants:
      - `const` keyword
      - `iota` built-in
    - Flow control
      - for `for {`
      - if / else if / else `if <statement>; <condition> {`
      - switch `switch {`
      - defers `defer <funcCall>`
    - More Types
      - Pointers `p := &<variable>`
      - Structs `type <name> struct {}`
      - Arrays `var <name> [<length>]int`
      - Slices `var <name> []int`
        - `len` & `cap`
      - Ranges `for <index>, <value> := range <iterable> {`
      - Functions `func <funcName>(<argName> <type>) ({<rVarName>} <type>) {`
    - Methods and interfaces
      - Receiver function `func (<varName> <receiverType>) <funcName>() {`
      - interfaces `type <interfaceNamer> interface {`