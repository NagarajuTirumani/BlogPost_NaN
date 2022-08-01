# NaN 

NaN stands for Not a Number. This property indicates that the data do not belong to the legal numbers(i.e, 0-9). 
Most of the time, We get NaN as the output in the following conditions.
	
1) When we try to get parse the invalid data, it returns NaN as the output.

  ###### Input:
  ```
  let value = "abc79"
  console.log(parseFloat(value));
  console.log(parseInt(value));
  console.log(Number(value));
  ```

  ###### Output:
  ```
  NaN
  NaN
  NaN
  ```

2) When a mathematical operation returns a non-real values, we will get NaN as the Output
     	
###### Input:
```
let value = Math.sqrt(-16)
console.log(value);
```	    
###### Output:
```
NaN
```

3)  when we did a mathematical operation with alphabets or special characters etc.
	
###### Input:
```
let value = "hello"* "hello"
console.log(value);
```
###### Output:
```
NaN
```
		
we can also check whether the data belongs to the legal number or not by using the isNaN method. If the data belongs to numbers, returns false or otherwise, it returns true. Let's see some examples. 
	
###### Input:
```
console.log(isNaN("120"))
console.log(isNaN("120abc"))
console.log(isNaN("Hello"))
```
###### Output:
```
false
true
true
```

You can read more about this [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NaN) 

also watch [here](https://youtu.be/0ZiltZDg9Gg)
	
