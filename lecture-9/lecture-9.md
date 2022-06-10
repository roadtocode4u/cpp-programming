
# Lecture-9  If-else-ladder

## Conditional Statements : 
There are Four Types : 
1. if 
2. if-else
3. if-else-ladder
4. nested-if

```cpp
3. if-else-ladder

syntax : 
if (condition 1)
{
    //-----
    //-----
}
else if(condition 2)
{
    //----
    //----
}
else if(condition 3)
{
    //----
    //----
}
else if(condition 4)
{
    //----
    //----
}
else
{
  //----
}
```

**💻 Example 1 :**
```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 2;

    if(num==1){
        cout<<"One";
    }
    else if(num==2){
        cout<<"Two"; 
    }
    else if(num==3){
        cout<<"Three"; 
    }
    else if(num==4){
        cout<<"Four"; 
    }
    else
    {
        cout<<"Not Matched :";
    }  
     return 0;
}
```
**⚙️ Output :**
>Two

**💻 Example 2 :**
```cpp
#include <iostream>
using namespace std;

int main() {
    int num = 8;

    if(num==1){
        cout<<"One";
    }
    else if(num==2){
        cout<<"Two"; 
    }
    else if(num==3){
        cout<<"Three"; 
    }
    else if(num==4){
        cout<<"Four"; 
    }
    else
    {
        cout<<"Not Matched...";
    } 
     return 0; 
}
```
**⚙️ Output :**
>Not Matched...

**💻 Example 3 :**
```cpp
#include <iostream>
using namespace std;

int main() {
    int marks;

    cout<<"Enter Marks:";
    cin>>marks;

    if(marks>90){
        cout<<"A";
    }
    else if(marks>80){
        cout<<"B"; 
    }
    else if(marks>70){
        cout<<"C"; 
    }
    else
    {
        cout<<"Fail";
    }  
     return 0;
}
```
**⚙️ Output :**
>Enter Marks : 85<br>
B

**💻 Example 4 :**
```cpp
#include <iostream>
using namespace std;

int main() {
    int marks;

    cout<<"Enter Marks:";
    cin>>marks;

    if(marks>90){
        cout<<"A";
    }
    else if(marks>80){
        cout<<"B"; 
    }
    else if(marks>70){
        cout<<"C"; 
    }
    else if(marks>60){
        cout<<"D"; 
    }
    else
    {
        cout<<"Fail";
    }  
     return 0;
}
```
**⚙️ Output :**
>Enter Marks : 25<br>
Fail

**💻 Example 4 : Boundry Condition**
```cpp
#include <iostream>
using namespace std;

int main() {
    int marks;

    cout<<"Enter Marks:";
    cin>>marks;

    if(marks>=70 && marks<=80>){
        cout<<"C";
    }
    else if(marks>=80 && marks<=90){
        cout<<"B"; 
    }
    else if(marks>=90 && marks <=100){
        cout<<"A"; 
    }
    else
    {
        cout<<"Invalid Number";
    }  

    return 0;
}
```
**⚙️ Output :**
>Enter Marks : 100<br>
A

**💻 Example 4 : Boundry Condition**
```cpp
#include <iostream>
using namespace std;

int main() {
    int marks;

    cout<<"Enter Marks:";
    cin>>marks;

    if(marks>=70 && marks<=80>){
        cout<<"C";
    }
    else if(marks>=80 && marks<=90){
        cout<<"B"; 
    }
    else if(marks>=90 && marks <=100){
        cout<<"A"; 
    }
    else
    {
        cout<<"Invalid Number";
    }  

    return 0;
}
```
**⚙️ Output :**
>Enter Marks : &880<br>
Invalid Number

## 🏠  HomeWork

## 🔗 Some Useful Links

## 📖 References



