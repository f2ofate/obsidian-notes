
```Go
var x, y int = 3, 4
var f float64 = math.Sqrt(x*x + y*y)
var z uint = uint(f)
fmt.Println(x, y, z) // ...(value of type int) as float64 value in argument to math.Sqrt
```

Что бы привести x,y используется приведение:

```Go
var x, y int = 3, 4
var f float64 = math.Sqrt(float64(x*x + y*y))
var z uint = uint(f)
fmt.Println(x, y, z) // 3 4 5
```