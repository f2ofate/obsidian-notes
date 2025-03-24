```Go
// Стандартный if/else/elif
if guess == x {
	return mid
} else if guess < x {
	low = mid + 1
} else {
	high = mid - 1
}
```

```Go
// Выбираем переменную (switch), если значение (cese) ... то ...
switch i {
case 1:
	fmt.Println("one")
case 2:
	fmt.Println("two")
case 3:
	fmt.Println("three")
}
```