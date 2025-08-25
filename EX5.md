# Ex.No:5  
# Ex.Name: Temperature Conversion (Celsius to Fahrenheit) using Class Methods  

## Date:  

## Aim:  
To write a C++ program to convert temperature from **Celsius to Fahrenheit** using class methods, where data members are declared as private and methods are defined inside the class.  

## Algorithm:  
1. Start the program.  
2. Define a class `Temperature` with:  
   - A private data member `celsius`.  
   - Public methods to:  
     - Read Celsius value.  
     - Convert Celsius to Fahrenheit using the formula:  
       \[
       Fahrenheit = (Celsius \times 9/5) + 32
       \]  
     - Display the results.  
3. In the `main()` function:  
   - Create an object of `Temperature`.  
   - Call the methods to read input, perform conversion, and display results.  
4. Stop the program.  

## Program:
```cpp
#include<iostream>
using namespace std;
class A{
    public:
    int c;
    void read(){
        cin>>c;
    }
    void dis(){
        cout<<"The temperature in Celsius:"<<c<<endl;
    }
};
class B:public A{
    public:
    void display(){
        cout<<"The temperature in Fahrenheit:"<<(c-((4/9)*100))<<endl;
    }
};
int main(){
    B zenko;
    zenko.dis();
    zenko.display();
}
```
## Output:
```
Input:
95

Output:
The temperature in Celsius:95
The temperature in Fahrenheit:203

Input:
78

Output:
The temperature in Celsius:78
The temperature in Fahrenheit:172.4
```
 ## Result:
<img width="861" height="503" alt="image" src="https://github.com/user-attachments/assets/aa8a0c1b-d854-45d5-8e43-e104199ed01b" />


