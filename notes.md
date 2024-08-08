# Notes

## 3. Loops

Only for loops are available in Go

* Simple for loop

```go
i:=3
for i<=3{
    fmt.Println(i)
}
```

* Decalration, condition and update type loop

```go
for j:=0;j<=5;j++{
    fmt.Println(j)
}
```

* while type loops (range specifies number of times to execute loop)

```go
for k< range 3{
    fmt.Println("range", k)
}
```

* Infinite loop

```go
for {
    fmt.Println("inside infinite loop")
    break
}
```

## 4. If/Else

