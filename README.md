CODE 1:
Step 1: Start

Begin program execution.

Step 2: Include Header File

Include the input-output stream library:

#include <iostream>


This allows the use of cout for displaying output.

Step 3: Use the std Namespace
using namespace std;


This allows access to standard library functions (like cout, endl) without needing std:: prefix.

Step 4: Define Class construct

Create a class named construct with:

Two private integer variables: a and b.

A public constructor.

A public member function called input().

Step 5: Define Constructor

The constructor is automatically called when an object of the class is created. It sets:

a = 10;
b = 20;

Step 6: Define Member Function input()

This function displays the values of a and b:

cout << "a=" << a << endl << "b=" << b;

Step 7: Main Function Begins Execution
int main()

Step 8: Create Object c of Class construct
construct c;


This automatically calls the constructor and sets a = 10, b = 20.

Step 9: Call the input() Function
c.input();


This prints the values of a and b.

Step 10: End the Program
return 0;
