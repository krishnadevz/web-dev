
**Recursion**
* Recursion is made for solving problems that can be broken down into smaller, repetitive problems. It is especially good for working on things that have many possible branches and are too complex for an iterative approach.in which recursion function calls itself. Ex:-searching through the File system 

**Interative fact**
```js

var factorial = function(n) {
    var result = 1;
for(var i=1;i<=n;i++){
result =result*i;

}

    return result;
};

println("The value of 5! should be " + 5*4*3*2*1);
println("The value of 5! is " + factorial(5));
println("The value of 0! should be 1");
println("The value of 0! is " + factorial(0));

Program.assertEqual(factorial(5), 120);
Program.assertEqual(factorial(0), 1);
Program.assertEqual(factorial(4), 24);
Program.assertEqual(factorial(3), 6);




```

**Recursive fact**
```js
var factorial = function(n) {
	// base case: 
	if(n === 0){
	    return 1;
	}
	else{
	return n*factorial(n-1);
	
	}
	// recursive case:
}; 

println("The value of 0! is " + factorial(0) + ".");
println("The value of 5! is " + factorial(5) + ".");

Program.assertEqual(factorial(0), 1);
Program.assertEqual(factorial(5), 120);
Program.assertEqual(factorial(4), 24);
Program.assertEqual(factorial(3), 6);

```
* memoization saves time of the program a form caching 
```js
def show_excitement():
    # Your code goes here!
    string="I am super excited for this course! " *5 
    return string

print show_excitement()
```


* BigO notation [Resource](https://www.bigocheatsheet.com/)
