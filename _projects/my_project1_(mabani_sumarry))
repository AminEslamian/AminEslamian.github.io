
## Arrays 

### bubble sort


### Searching arrays:
- **linear search:**
	Starts from the first home in array and searches every member for the wanted value and returns the index of the first home with the wanted value.
- **Binary search:**
	 If the array is sorted, the high-speed binary search technique can be
	used.
	 The binary search algorithm eliminates from consideration one-half of the
	elements in a sorted array after each comparison.
	 The algorithm locates the middle element of the array and compares it to the
	search key.

### Different ways for using functions
- Writing the main code first, while imagining that the functions will work correctly. Then we write the structure of the functions.
- Writing the functions first and checking if each work correctly, then we write the main function.

### Multiple-Subscripted Array
* definition example: int arr \[ 2 ] \[ 3 ]
* You can imagine them as a table, that first number defines the rows, and the second one defines the columns.
* for declaring them in functions it is needed to specify the size of inside arrays (or the size of each row in our imagination); 
example: int func(int arr \[ ] \[ 3 ]);



## Pointer

### Intro:

	int a;    
	int *aptr;
	a = 7;    
	aptr = &a;
	
* &\<variable> means address of the variable.
* \*\<variable(a pointer type variable)> takes the value of were the pointer is pointing to. 


**example:**
![[Pasted image 20241231131450.png]]
### Passing Arguments to Functions by Reference
* **Call by value:**
	void cubeByValue (int n);
	int main () {
	int number;
	...
	cubeByValue (number);
	}
* **Call by reference:**
	void cubeByReference (int \*nptr);
	int main () {
	int number=7;
	....
	cubeByReference (&number);
	}

**Point:** *The difference between giving b\[ ] or \*b as an argument to a function is that, despite they are both pointers, b\[ ] is constant! (b\[ ] is an array, or in the same meaning the address of beginning of the array.)*

### Constancy in Pointers
Different modes: 
* const char \*sPtr 
* char \* const sPtr
* const char \* const sPtr
* char \*sPtr

**example1:**
![[Pasted image 20241231142616.png]]
	in line 12: The definition is read from right to left as “ptr is a
constant pointer to an integer.”


**example1:**
![[Pasted image 20241231142719.png]]
	in line 13: is read from right to left as “ptr is a
constant pointer to an integer constant.”
	**point:** In the case of defining a constant pointer, it's value has to be given while initialization (definition).
