<h1>Numeric data type</h1>
 In the Numeric type, there are 4 types
 
 1. Int
 2. Binary
 3. Octa
 4. Hexa  
 

<h3>Int</h3>
We can use the int data type to represent whole numbers (integral values).

     Eg:  a=10
     type(a) #int is the output

In Python 2, we used to use long int to enter long numbers,  
But in Python 3, there is no long type explicitly.  
We can represent them by using int  

<h3>Binary</h3>
It is used to represent the 0 and 1  

eg

     a=0b1010, b=0b1111
Here, 0b is used to represent that it is a binary.

<h3>Octal</h3>
Here, 0c is used to represent that it is an octal  

It uses a base-8 system with digits 0 through 7 to represent numbers, where each digit's place value is a power of 8  
Digits: The system uses only the digits 0, 1, 2, 3, 4, 5, 6, and 7.  
Base-8: The "oct-" in octal refers to eight(8), just as "dec-" in decimal refers to ten(10).

Example: The octal number 112 would be converted to decimal as (1 * 8^2) + (1 * 8^1) + (2 * 8^0) = 64 + 8 + 2 = 74. 

<h3>hexa</h3>
Here, 0x is used to represent that it is hexadecimal  

E.g. a=0x in a normal number, its value is 42. When we try to print it, we have to use print(a) to get the 42 as the output  
And we can convert from one to another as shown in the table below.

<img width="1312" height="380" alt="image" src="https://github.com/user-attachments/assets/6e41e5ee-ac76-4e59-be21-4d3a0d391a57" />

Float data type
===============
A number with a decimal point is known as float number

    eg. 10.23, 3.14
Like we have converted numeric data types one to another, here we can't convert.  
But there are many ways to represent floating-point numbers

<h3>Standard (decimal representation)</h3>
This is used for short numbers

     a=10.23, b=-1.24, c=0.452
     
But if there is a big decimal number, then it would be hard to write. To overcome this, we use 

<h3>Scientific (Exponential) Notation</h3>  
The main advantage of this Exponential notation is that when there is a long decimal number, we will use this method.

	I/P	OPERATION	O/P
					c=1.5e3	    1.5× 10³	1500.0
					d = 2E-4	2 × 10⁻⁴	0.0002
					e= 1.5e8	1.5 x 10³	150000000.0
     
<h4>Summary</h4> 

      Ways to represent a float in Python: 
     a) Decimal form (3.14)  
     b) Scientific notation (1.5e8) =====>150000000.0 
     c) Leading/trailing dot (.5, 10.)  
     d) Special values (inf, -inf, nan) 
     e) Underscore separators (1_000.5) 
     f) Casting from int/string (float(5), float("3.14"))  =====> converts from int/string to float

Complex data type
==================
It is a specific data type in Python.  
A complex number has two parts: real and imaginary, where the imaginary unit is written as j (or J).  
We can represent real numbers in decimal, binary, octa, hexa and float  but imaginary numbers can be represented only in decimal or float form only.

	e.g.		input            output
				z1= 3 + 5j	    print(z1.real)= 3	 print(z1.imag)= 5
				z2= -2 - 4j	    print(z2.real)= -2	 print(z2.imag)= -4
				z3=0b1010+2j	print(z3.real)= 10	 print(z3.imag)=2
				z4=2+0b1010j	output is syntax error because the imaginary unit is binary.
