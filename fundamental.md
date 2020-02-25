#fundamental

Line #1: using System;

Comment:  /*, */--- (start-end), // --- (one line) 

Class MyClass ----- everything in C# is part of something known as a class

{        
}  -------- start and end of a block of code(scope)

Which in brace ---- function declaration: function(argument)

Static , void : keywords in C#

; : terminate

using System;

class MyClass
{
static void Main(string[] args)
{
System.Console.Write("one, ");

System.Console.Write("two, three, ");

System.Console.Write("four & ");

System.Console.WriteLine("five");
}
}

##Variable in C# 

Bool b;  // boolean 

- b1 = true; b2 = false;

Char c;  // character

-single quote: 'a', 'B', '$', '9', can use +

Float f;  // floating point, single precision

-e.g 1.23f

Double d; // floating point, double precision

-e,g 1.234

Decimal e; // floating point, more bits than 'double'

-e.g 1.234m

Int I;  // integer

Long m; // long integer

- The minimum size for char is 8 bits, the minimum size for short and int is 16 bits, for long it is 32 bits 

- We could initial or uninitial variables

- $ at the start then all the text in one pair of double quotes

- {Bool b1 = true, b2 = false;}   =    Console.WriteLine($''bool1 = {b1}, bool2 = {b2}")

##others

Print output to the console: WriteLine

Read input from the console: ReadLine

convert to int, double and bool: .Parse(), e.g.int.Parse(); doule.Parse(); bool.Parse();

&&: and

||: or


Math.Round: Rounds a value to the nearest integer or to the specified number of fractional digits.
("四舍六入五考虑，五后非零就进一，五后皆零看奇偶，五前为偶应舍去，五前为奇要进一")

/ ----- if integer, integer division. if double var, e.g 1/4=0, 1.0/4.0=0.25 (no round) 

% ----- remainder

<>=: comparison operator --- result: bool

Random: next(n): random positive number smaller than n; next(a, b): random positive number between a and b

##array

New: allocate memory (e.g. declare an array of length n: int n =10; double[] b = new double [n]; assign value: b[m] = m == double[] b = {a, b, c, d};)
- Length: .length

2d rectangular array: e.g. double[,] c = new double [m,n]; assign vaue: c[I, j] = x*i + y*j
- Length:.GetLength(0/1)

2d jagged array: e.g. int[][] t = new int[m] [] ; assignment: first, assign m, then assign value: t[i][j] = x*I + y*j

- length: t.length for outer loop, t[i].length for inner loop

-comparision: ra[I , j]   ja[i] [j]; ja has less memory than ra

Resize: when an array is resized, all the previously stored data is lost

## Shortcut

X = x + y;
X += y

X = x - y;
X -= y

X = x * y;
X = x *= y

X /= y;
X = x / y

postfix: increment/decrement and fetch (return old value)

X = x + 1;
X ++

X = x - 1;
X --

prefix: fetch and increment/decrement (return new value)

++ x
-- x

##Loop:
- For(start condition, end condition)

- While(end-of-loop condition)

Nested loop: allows to use one loop inside another loop

For different line in the loop condition, execute loop body code when these are true, terminated when false.
For different loop, cause the early loop terminates, when the next loop execute, variable I is not the same

Break: exit the loop ( if break in inner loop, the program execution will exit to the outer loop)

Continue: go to the next pass of the loop

- If() ---- conditional statement

If (condition1){
   code1
}
Else if (condition 2){
   code2
}
Else{
   code3
}

