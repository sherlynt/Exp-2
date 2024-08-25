# Exp-2

AIM: To study and implement C++ data structures.

SOFTWARE: Visual Studio Code

THEORY:

The sizeof operator in C++ returns the size (in bytes) of a variable or data type. This operator is evaluated at compile time and provides information about the memory allocated for each data type.

a.sizeof(char): Typically returns 1 byte, as the size of char is defined to be 1 byte in C++.

b.sizeof(int): The size of int is system-dependent but usually 4 bytes on most modern systems.

c.sizeof(short int): Usually 2 bytes, though this can vary depending on the system.

d.sizeof(long int): Often 4 or 8 bytes, depending on the system architecture (e.g., 4 bytes on 32 bit systems and 8 bytes on 64-bit systems).

e.sizeof(float): Generally 4 bytes.

f.sizeof(double): Typically 8 bytes.

g.sizeof(long double): Can vary but is often 12 or 16 bytes.

h.sizeof(bool): Often 1 byte, though this can vary.

CODES:

```
#include<iostream>
using namespace std;

int main()
{
    cout<< "size of char: " <<sizeof(char) << "byte(s)" <<endl;
     cout<< "size of int: " <<sizeof(int)<< "byte(s)" <<endl;
     cout<< "size of short int: " <<sizeof(short int) << "byte(s)" <<endl;
     cout<< "size of long int: " <<sizeof(long int) << "byte(s)" <<endl;
     cout<< "size of float : " <<sizeof(float) << "byte(s)" <<endl;
     cout<< "size of double: " <<sizeof(double) << "byte(s)" <<endl;
     cout<< "size of long double: " <<sizeof(long double) << "byte(s)" <<endl;
     cout<< "size of bool: " <<sizeof(bool) << "byte(s)" <<endl;
     return 0;
}
```
OUTPUT 1: ![image](https://github.com/user-attachments/assets/8dfe30d4-e5cb-43fd-aabf-f72c09d3f30d)


```
#include <iostream>
using namespace std;

int main()
{
    int a;
    cout<<"Enter any integer: ";
    cin>>a;
    cout<<"\n Integer = "<<a<<" and size is "<<sizeof(a)<<" bytes";
    
    float b;
    cout<<"\n Enter a number: ";
    cin>>b;
    cout<<"\n Float= "<<b<<" and size is "<<sizeof(b)<<" bytes";
    
    short int c;
    cout<<"\n Enter an interger: ";
    cin>>c;
    cout<<"\n Short integer = "<<c<<" and size is "<<sizeof(c)<<" bytes";
    return 0;
}
```
OUTPUT 2: ![image](https://github.com/user-attachments/assets/7f3b78c0-3405-4985-bf62-d9c4035ab82c)


```
#include <iostream>
using namespace std;
int main(){
    int a;
    cout<<"Enter any integer:";
    cin>>a;
    cout<<"\nInteger= "<<a<<"and size is "<<sizeof(a)<<"bytes";

    int b;  
    cout<<"\nEnter a number:";
    cin>>b;
    cout<<"\nREGISTER="<<b<<"and size is"<<sizeof(b)<<"bytes";

    int c;  
    cout<<"\nEnter an integer: ";
    cin>>c;
    cout<<"\nAuto="<<c<<"and size is"<<sizeof(c)<<"bytes";

    return 0;
}
```
OUTPUT 3:![image](https://github.com/user-attachments/assets/67bc797d-5f29-4f04-a3a8-ff66d84fa7c0)


CONCLUSION:
When the code is run, different C++ data types' sizes in bytes are displayed. The architecture and compiler of your computer may cause these sizes to vary. Understanding these sizes will help you optimize your applications and make sure they operate well on various systems by revealing how much memory different categories require.
