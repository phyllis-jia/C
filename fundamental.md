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
