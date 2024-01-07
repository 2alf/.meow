# .meow
Simple interpreted programming language

Made as an educational project.
Succeded in basic functionality will try advancing it in the future.
Math, vars, loops work. To add: functions, direct printing.

vars:
`let x := "John Doe"`

print:
`log "Hello, World!"`
```
let x := 10
log x
```
func ( WIP ):
```
func add(a, b):
    :3 a + b;
end
```


## fibonacci in .meow:
Source:
```
let n := 10
let a := 0
let b := 1
let i := 0
let temp := 0

while i < n:
    log a
    let temp := a
    let a := b
    let b := temp + b
    let i := i + 1
end
```
Output:
```
0
1
1
2
3
5
8
13
21
34
```

## drawing in .meow:
```
let height := 10

let row := 0
while row <= height:
    let spaces := height - row - 1
    let stars := row + 1

    let star_line := ""

    let i := spaces
    while i > 0:
        let space_str := " "
        let i := i - 1
    end

    let i := stars
    while i > 0:
        let star_str := "*"
        let star_line := star_line + star_str
        let i := i - 1
        log star_line 
    end

    let row := row + 1
end

```
Output:
```
  *
  *  *
  *  *  *
  *  *  *  *
  *  *  *  *  *
  *  *  *  *  *  *
  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *  *  *  *  *  *  *
  *  *  *  *  *  *  *  *  *  *  *  *  *  *  *
```

## reversing a string:
Source:
```
let input_str := "hello"
let reversed_str := ""

let i := len(input_str) - 1
while i >= 0:
    let reversed_str := reversed_str + input_str[i]
    let i := i - 1
end

log reversed_str

```
Output:
```
  o
  ol
  oll
  olle
  olleh
```

More to come.
