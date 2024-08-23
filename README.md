# Experiment-6
## Aim -
To study and implement C++ decision making statement loops

## Theory -
Loops are used to make the program less repetitive and compact ny iterating a part of a program several times .Thus,they are also called repetitive control structures.

### Types of loops:-

### A) For Loop -
A "for" loop is a control flow statement used to repeat a block of code a certain number of times.

The syntax can vary slightly depending on the programming language.

### B) While loop:-
A "while" loop is another type of control flow statement that repeatedly executes a block of code as long as a specified condition is true.

You can control the flow inside a "while" loop using break to exit the loop and continue to skip to the next iteration:

### C) Do-while loop:-
It executes the block of code at least once before checking the condition. Python does not have a built-in "do-while" loop, but you can simulate it.

You can control the flow inside a "while" loop using break to exit the loop and continue to skip to the next iteration:

Nested loops:-
Nested loops involve placing one loop inside another. They can be useful for handling multi-dimensional data or performing complex iterations.

Nested loops can be quite powerful but can also lead to performance issues if not used carefully, especially with large datasets or high iteration counts.

## Code:-
### 1. For loop
~~~
//Soham
//23070123084
//entc B1
//experiment 6
#include<iostream>
using namespace std;
int main()
{
    int i;
    for(i=0;i<10;i++)
    {
        cout<<"Hello world("<<i+1<<")"<<endl;
    }
}
~~~
### 2. while loop
~~~
//Soham
//23070123084
//entc B1
//experiment 6B
#include<iostream>
using namespace std;
int main() 
{
    int input = 1;
    while (input <= 15) {
        std::cout << "\n" << input;
        input++;
    }
}
~~~
### 3. Do-while
~~~   
//Soham
//23070123084
//entc B2
//experiment 6C
#include <iostream>

using namespace std;

int main() {
    int number = 1;
    do {
        cout << number << endl;
        number++;
    } while (number <= 10);
    return 0;
}
~~~
### 4. Nested for loop
~~~
//subham
//23070123132
//entc B2
//experiment 6D
#include<iostream>
using namespace std;
int main() {
    for (int i = 1; i <= 1; i++) {
        for (int j = 1; j <= 10; j++) {
            std::cout << j << " ";
        }
    }
    std::cout << std::endl;
    return 0;
}
~~~
### 5. Nested while
~~~
//Soham
//23070123084
//entc B1
//experiment 6E
#include<iostream>
using namespace std;
int main()
{
    int i = 1;
    while (i <= 10) {
        int j = 1;
        while (j <= i) {
            std::cout << j << " ";
            j++;
        }
        std::cout << std::endl;
        i++;
    }
    return 0;
}
~~~
### 6. Nested do while
~~~
//Soham
//23070123084
//entc B1
//experiment 6F
#include<iostream>
using namespace std;
int main() {
    int i = 1;
    do {
        int j = 1;
        do {
            std::cout << j << " ";
            j++;
        } while (j <= 10);
        i++;
    } while (i <= 1);
    std::cout << std::endl;
    return 0;
}
~~~
### 7. Nested for while
~~~
//Soham
//23070123084
//entc B1
//experiment 6G
#include<iostream>
using namespace std;
int main()
{
    int i,j,k=0,n;
    cout<<"Enter number of rows-";
    cin>>n;
    for(i=1;i<=n;i++)
    {
        for(j=1;j<=(n-i);j++)
        {
            cout<<" ";
        }
        while(k!=(i-1))
        {
            cout<<"* ";
            k++;
        }
        k=0;
        cout<<endl;
    }
    cout<<endl;
}
~~~
## Explanation:-
Loops allow repetitive execution of code. A for loop iterates over a sequence and is used when the number of iterations is known.

A while loop runs as long as a condition is true, useful for uncertain iteration counts.

Nested loops enable complex iteration, such as iterating over multi-dimensional arrays. Each type offers different control and flexibility for managing code flow.

## Output:-
### 1. For loop
![image](https://github.com/user-attachments/assets/8efc8af0-2d52-4f69-8ff6-50be0af3b167)


### 2. While loop
![image](https://github.com/user-attachments/assets/77db3af9-302b-41ec-a2c3-01dc58b3f680)


### 3. Do-While loop
![image](https://github.com/user-attachments/assets/f44feb9d-2b18-47ab-b223-d7260badc3d1)


### 4. Nested for loop
![image](https://github.com/user-attachments/assets/f452c0d3-de99-4bba-824e-baf89e8dd64c)


### 5 .Nested while loop
![image](https://github.com/user-attachments/assets/0466ffc7-113b-41d7-a5d7-1df83350172b)


### 6. Nested do-while loop
![image](https://github.com/user-attachments/assets/79464944-4b28-4746-b84a-a05cd22f8abf)


### 7. Nested for while loop
![image](https://github.com/user-attachments/assets/d081b1be-af67-4fd1-9fe5-76cadf9372ae)


## Conclusion:-
Decision-making statements like if, elif, and else control code execution based on conditions, while loops (for and while) repeat code blocks. Combining these allows dynamic, responsive programming. For example, using if statements within loops enables actions based on conditions during each iteration, efficiently handling varying data and scenarios.
