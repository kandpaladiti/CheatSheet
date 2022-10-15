Java Programming

Java is a high-level, general-purpose programming language that produces software for multiple platforms. It was developed by James Gosling in 1991 and released by Sun Microsystems in 1996 and is currently owned by Oracle.

Primitive Data Types
Type		Size		Range
byte		8 		-128..127
short		16             	 -32, 768..32, 767
int		32		-2, 147, 483, 648..2, 147, 383, 647
long		64		-9,223,372,036,854,775,808.. 9,223,372,036,854,775,807
float		32		3.4e-0.38.. 3.4e+0.38
double		64		1.7e-308.. 1.7e+308
char		16		Complete Unicode Character Set
Boolean	1		True, False

Java Operators
Operator Type			Operators
Arithmetic				+, – , *, ? , %
Assignment				=, +=, -=, *=, /=, %=, &=, ^=, |=, <<=, >>=, >>>=
Bitwise					^, &, |
Logical 					&&, ||
Relational				<, >, <=, >=,==, !=
Shift					<<, >>, >>>
Ternary					?:
Unary					++x, –x, x++, x–, +x, –x, !, ~

Java Variables
Variables in Java refers to the name of the reserved memory area. You need variables to store any value for the computational or reference purpose.
There are 3 types of variable in Java:
1.	Local Variables
2.	Instance Variables
3.	Static Variables
{public  |  private}  [static]  type name  [= expression  |  value];

Java Methods
A method is a set of code that is grouped together to perform a specific operation. A method is completed in two steps:
1.	Method Initialization
2.	Method Invocation
A method can be invoked either by calling it by reference or by value.
{public | private} [static] {type | void} name(arg1, ..., argN ){statements}

Data Conversion
The process of changing a value from one data type to another type is known as data type conversion. Data Type conversion is of two types:
1.	Widening: The lower size datatype is converted into a higher size data type without loss of information.
2.	Narrowing: The higher size datatype is converted into a lower size data type with a loss of information.

// Widening (byte<short<int<long<float<double)
int i = 10; //int--> long
long l = i; //automatic type conversion
// Narrowing 
double d = 10.02;
long l = (long)d; //explicit type casting
// Numeric values to String
String str = String.valueOf(value);
// String to Numeric values
int i = Integer.parseInt(str);
double d = Double.parseDouble(str);

User Input
Java provides three ways to take an input from the user/ console:
1.	Using BufferReader class
2.	Using Scanner class
3.	Using Console class

// Using BufferReader
BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
String name = reader.readLine();
// Using Scanner
Scanner in = new Scanner(System.in);
String s = in.nextLine();
int a = in.nextInt();
// Using Console
String name = System.console().readLine();

Basic Java Program
A basic program in Java will consist of at least the following components:
1.	Classes & Objects
2.	Methods
3.	Variables

public class Demo{ 
  public static void main(String[] args) 
   { System.out.println("Hello from edureka!");}
}

