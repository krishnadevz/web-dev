
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
*  LinkedList is something that has a head Element, which is the first element in the list. If we establish a new LinkedList without a head, it will default to None. 
*  complexity of binary search is O(log2n)=Olog(n)
*  In bubble sort naive approach compare with everyone compare and then switch the elements
*  * merge sort divide array into the small ones and then merge it it's called divide and conquer.merge sort complexity = o(nlogn)
*  Quick sort is the one of the efficient algorithm pivot compare greater than and then swap O(nlogn)
*  ![Screenshot from 2021-04-21 13-20-15](https://user-images.githubusercontent.com/42638797/115517038-5e939a80-a2a4-11eb-84d3-d5bdee1cb6ad.png)

**Dynamic programming**:-if we can break problem into subproblems then it can be done with help of dynamic programming.
run time in exponentials.


