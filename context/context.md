# js上下文

## 变量提升

- var 变量提升，再function
  ```js
	function a(){}
	var a ;
	console.log(a) //ƒ a(){}
	```

	## 上下文
	- 上下文存储了变量
  ## 作用域
	- 到对应作用域的上下文寻找变量