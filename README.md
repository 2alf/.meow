# .meow
Simple interpreted programming language

Made as an educational project.
Succeded in basic functionality will try advancing it in the future.
Math, vars, loops work. To add: functions.

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

fibonacci in .meow:
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
