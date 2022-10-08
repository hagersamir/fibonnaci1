<!-- Headings -->
# fibonacci 
## fibonacci sequence 
### fibonacci sequence problem 
<!-- Italic -->
*This is italic words* 
_This is italic words_
<!-- bold -->
**This is bold words**
__this is bold words__
<!-- Strikethrough -->
~~This is strikethrough~~
<!-- Horizontal Rule -->
---
Hager Samir
___
 <!-- UL -->
 * Item 1
 * Item 2
 * Item 3
   * Nested Item 1
   * Nested Item 2
 <!-- OL -->
1. Item 1
1. Item 2
1. Item 3 
<!-- Code Block -->
```
#include<iostream>
using namespace std;
int main()
{
int first_num = 0, second_num = 1, third_num, i, num;
cout << "Enter random number to print fibonacci series:";
cin >> num;
cout << "Fibonacci Series for a given number:" <<endl;
cout << first_num  <<endl;
cout << second_num << endl;
for(i = 2; i < num; ++i) //loop will starts from 2 because we have printed 0 and 1 before
{
third_num = first_num + second_num;
cout << third_num << endl;
first_num = second_num;
second_num = third_num;
}
return 0;
}
```
```
#include<iostream>
using namespace std;
int main()
{
int first_num = 0, second_num = 1, third_num = 0, i = 3, num;
cout << "Enter random number to print fibonacci series:" ;
cin >> num;
cout << "Fibonacci Series for a given number:" <<endl;
cout <<  first_num <<endl;
cout << second_num <<endl;
while(i <= num)
{
third_num = first_num + second_num;
cout << third_num <<endl;
first_num = second_num;
second_num = third_num;
i = i + 1;
}
return 0;
}
```
```
#include<iostream>
using namespace std;
int main()
{
int fibonacci[25], i, num;
cout << "Enter random number to print fibonacci series:";
cin >> num;
fibonacci[0] = 0;
fibonacci[1] = 1;
for (i = 2; i < num; i++)
{
fibonacci[i] = fibonacci[i - 1] + fibonacci[i - 2];
}
cout <<"Fibonacci Series for a given number:" << endl;
for (i = 0; i < num; i++)
{
cout << fibonacci[i] <<endl;
}
return 0;
}
```
<!-- Tables -->
|Name    | Email                            |
|--------|----------------------------------|
|Hager   | hagersamir93@gmail.com           |        
|Hager   | hajar.elsayed00@eng-st.cu.edu.eg |
<!-- Links -->
 [Vedantu](http://www.vedantu.com)

<!-- Image -->
![fibonacci image](https://media.istockphoto.com/vectors/scheme-of-golden-ratio-section-fibonacci-spiral-on-blackboard-vector-vector-id1249776994) 