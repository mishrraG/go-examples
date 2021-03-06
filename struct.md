---
layout: default
---

# Structs

Example demonstrates structs. Structs are used to group one of more fields of logical types together.
Click [here](https://tour.golang.org/moretypes/2) to learn more

```go
//For example we could represent a Point struct as:
type Point struct {
	x int
	y int
}

func main() {

	//Then in order to use it we need to initialize it. 
	//There are 3 ways to initialize a struct in Go.
	var c Point
	c := Point{x: 1, y: 2}

	//Once you have a struct instance 
	//you can access its fields using the dot . operator:

	fmt.Println(c.x) // 1
	c.x = 10         //updating value
	fmt.Println(c.x) // 10

}

```
### Output

```bash
1
10
```

<a href='https://play.golang.org/p/3WTvfovnEXn' target='_blank'>Try It Out</a> | <a href='https://github.com/sagar-jadhav/go-examples/blob/master/src/struct.go' target='_blank'>Source Code</a>

### Contributors
- <a href='https://github.com/LukaJaj' target='_blank'>Luka Jajanidze</a>
- <a href='https://github.com/mmichaelb' target='_blank'>Michael B.</a>
- <a href='https://github.com/aprabhat' target='_blank'>Prabhat Agarwal</a>

[<< Home Page](./) | [Previous << Interface](./interfaces.html) | [Next >> Stack](./stack.html)
