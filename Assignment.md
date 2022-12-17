What do you mean by operator?expplain bitwise operator in detail with proper explanations and examples of each.</br>
Operator is a symbol used to perform operation between two or more operands.The bitwise operators are the operators
used to perform the operations on the data at the bit level. Bitwise operator convert the numbers into binary bits and 
perform operation. there are several types of bitwise operator.</br>
1.Bitwise AND(&)</br>
 The output of bitwise AND is 1 if the corresponding bits of two operand is 1.If either bit of an operand is 0,the result of corresponding
 bit is evaluated to 0.</br>
 2.Bitwise OR(|)</br>
  The output of bitwise OR is 1 if at leat one corresponding bit of two operandddds is 1.It is denoted by (|).</br>
 3.Bitwise NOT(~)</br>
  Bitwise NOT or complement operator is a unary operator. It chnages 1 to 0 and 0 to 1.</br>
 4.Right shift operator(>>)</br>
  Right shift operator shifts all bits towards right by certain number of specified bits. It is denoted by (>>).</br>
 5.Left shift operator</br>
  Left shift operator shifts all bits towards left by a certain number of specified bits.</br>
  The symbol of the left shift operator is (<<).</br>
  
  Examples of bitwise operator:-
  1. Bitwise AND operator
  ```cpp
  #include<iostream>
using namespace std;
int main()
{
    int a=10,b=5,c;
    c=a&b;
    cout<<"c="<<c<<endl;
    return 0;
}
```
2. Bitwiae OR operator
```cpp
#include<iostream>
using namespace std;
int main()
{
    int a=10,b=5,c;
    c=a|b;
    cout<<"c="<<c<<endl;
    return 0;
}
```
3.Bitwise NOT operator
```cpp
#include<iostream>
using namespace std;
int main()
{
    int a=5,b;
    b=~a;
    cout<<"b="<<b<<endl;
    return 0;
}
```
4.Right shift operator
```cpp
#include<iostream>
using namespace std;
int main()
{
    int a=5,b;
    b=a>>2;
    cout<<"b="<<b<<endl;
    return 0;
}
```
5.left shift operator
```cpp
#include<iostream>
using namespace std;
int main()
{
    int a=5,b;
    b=a<<2;
    cout<<"b="<<b<<endl;
    return 0;
}
```

