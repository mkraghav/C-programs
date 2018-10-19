## WHILE LOOP

A while loop statement repeatedly executes a target statement as long as a given condition is true.

## Syntax :

The syntax of a while loop in C++ is −
````C++
while(condition) 
{
   statement(s);
   update expression;
}
````

Here, statement(s) may be a single statement or a block of statements. The condition may be any expression, and true is any non-zero value. The loop iterates while the condition is true.

When the condition becomes false, program control passes to the line immediately following the loop.

## Flow Diagram :

![cpp_while_loop](https://user-images.githubusercontent.com/35162705/47104631-85019680-d25f-11e8-83f5-975c9f7a0678.jpg)


Here, key point of the while loop is that the loop might not ever run. When the condition is tested and the result is false, the loop body will be skipped and the first statement after the while loop will be executed.

## Examples :
// C++ Program to compute factorial of a number

#include<iostream>
   
using namespace std;

int main() 

{
    int number, i = 1, factorial = 1;

    cout << "Enter a positive integer: ";
    cin >> number;
    
    while ( i <= number) {
        factorial *= i;      //factorial = factorial * i;
        ++i;
    }

    cout<<"Factorial of "<< number <<" = "<< factorial;
    return 0;
}

//Output

Enter a positive integer: 4
Factorial of 4 = 24

**Cheers :beers:**
