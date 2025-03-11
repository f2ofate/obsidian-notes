``` Go
// Цикл for классический
for i := 0; i < 5; i++ { // init; condition; post-action (i++ = i + 1)
    fmt.Println(i)
}
```

``` Go
// Цикл while
x := 0
for x < 5 { // condition
    fmt.Println(x)
    x++
}
```

``` Go
// Цикл range
numbers := []int{10, 20, 30}
for index, value := range numbers { // index, value = range slice/array/...
    fmt.Printf("Index: %d, Value: %d\n", index, value)
}
// u can skip index or value if enter _ ( for _,index = rande ...)
for _, value := range numbers {
    fmt.Println(value)
}
```