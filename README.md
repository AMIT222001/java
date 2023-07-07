
Java notes
--------------------------------------------------------------------------------------------------------------------------
Basic Syntax
Understanding the basics is the key to a solid foundation. In this section, learn the basic terminologies, naming conventions, reserved words, conditions, functions, data structures, OOP, packages, etc.

To print output use —> System.out.println();
To take input from user —> Scanner or BufferedReader class can be used
---------------------------------------------------------------------------
VARIABLES  
Types of variables
In Java, there are three types of variables:

Local Variables
Instance Variables
Static Variables
1) Local Variables
Local Variables are a variable that are declared inside the body of a method.

2) Instance Variables
Instance variables are defined without the STATIC keyword .They are defined Outside a method declaration. They are Object specific and are known as instance variables.

3) Static Variables
Static variables are initialized only once, at the start of the program execution. These variables should be initialized first, before the initialization of any instance variables.

Example: Types of Variables in Java
class Guru99 {
    static int a = 1; //static variable  
    int data = 99; //instance variable  
    void method() {
        int b = 90; //local variable  
    }
}

--------------------------------------------------------------------------------------------------------------------------
