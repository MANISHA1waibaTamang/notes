1.enter a value of length and breadth of a rectangle from user and check if it is square or not.
```cpp
#include<iostream>
using namespace std;
int main()
{
    int l,b;
    cout<<"enter a length:";
    cin>>l;
    cout<<"enter a breadth:";
    cin>>b;
    if(l==b)
    {
        cout<<"it is square";
    }
    else
    {
        cout<<"it is rectangle";
    }
}
```

2.A shop will give discount of 10% if the cost of purchased quantity is more than 1000.Ask user for quantity. 
suppose,one unit will cost 100. judge and print total cost for user.
```cpp
#include<iostream>
using namespace std;
int main()
{
    int qty,price,discount,totalcost;
    cout<<"enter quantity:";
    cin>>qty;
    cout<<"enter price:";
    cin>>price;
    totalcost=qty*price;
    if (totalcost>1000)
    {
        discount=(totalcost*0.1);
        totalcost=totalcost-discount;
    }
    cout<<"the total cost is Rs."<<totalcost;
    return 0;
}
```

3.A company decided to give bonus of 5% too employee if his/her year of service is more than 5 years of service
and print net bonus amount.
```cpp
#include<iostream>>
using namespace std;
int main()
{
    int salary,bonus,year;
    cout<<"enter a salary of employee:";
    cin>>salary;
    cout<<"enter a year of service:";
    cin>>year;
    if(year>5)
    {
        bonus=salary*0.05;
    }
    cout<<"the net bonus amount is Rs."<<bonus;
    return 0;
}
```
4. Check whether a number is even or odd.
```cpp
#include<iostream>
using namespace std;
int main()
{
    int num;
    cout<<"enter a number:";
    cin>>num;
    if(num%2==0)
    {
        cout<<"the number is even";
    }
    else
    {
        cout<<"the number is odd";
    }
    return 0;
}
```

5.program to check whether a number is divisible by 5 and 11 or not.
```cpp
#include<iostream>
using namespace std;
int main()
{
    int num;
    cout<<"enter a number:";
    cin>>num;
    if(num%5==0 && num%11==0)
    {
        cout<<"the number is divisible by 5 and 11.";
    }
    else
    {
        cout<<"the number is not divisible by 5 and 11.";
    }
    return 0;
}
```
6.Program to check whether the triangle is an equilateral,isosceles or scalene triangle.
```cpp
#include<iostream>
using namespace std;
int main()
{
    int side1,side2,side3;
    cout<<"enter a side1:";
    cin>>side1;
    cout<<"enter a side2:";
    cin>>side2;
    cout<<"enter a side3:";
    cin>>side3;
    if(side1==side2&&side2==side3)
    {
        cout<<"the triangle is equilateral.";
    }
    else if(side1==side2||side2==side3||side1==side3)
    {
        cout<<"the triangle is isosceles.";
    }
    else 
    {
        cout<<"the triangle is scalene.";
    }
    return 0;
}
```
7.Program to calculate profit or loss.
```cpp
#include<iostream>
using namespace std;
int main()
{
    int sp,cp,loss,profit;
    cout<<"enter a cost price:";
    cin>>cp;
    cout<<"enter a selling price:";
    cin>>sp;
    if(sp>cp)
    {
        profit=sp-cp;
        cout<<"the profit is Rs."<<profit;
    }
    else if(cp>sp)
    {
        loss=cp-sp;
        cout<<"the loss is Rs."<<loss;
    }
    else
    {
        cout<<"neither profit nor loss";
    }
}
```
8.Program to check whether a year is a leap year or not by using an if else statement.
```cpp
#include<iostream>
using namespace std;
class year
{
    int year;
    public:
    void input()
    {
        cout<<"enter a year:";
        cin>>year;
    }
    void output()
    {
    if(year%4==0)
    {
        cout<<year<<" is leap year";
    }
    else
    {
        cout<<year<<" is not a leap year";
    }
    }
};
int main()
{
    year y1;
    y1.input();
    y1.output();
    return 0;
}
```
9.Program that checks whether the character is an alphabet or not.
```cpp
#include<iostream>
using namespace std;
class character
{
    char c;
    public:
    void input()
    {
        cout<<"enter a character:";
        cin>>c;
    }
    void output()
    {
        if((c>='a' && c<='z')||(c>='A' && c<='Z'))
        {
            cout<<"character is alphabet"<<c;
        }
        else
        {
            cout<<"character is not alphabet"<<c;
        }
    }
};
int main()
{
    character c1;
    c1.input();
    c1.output();
    return 0;
}
```
10.Program to check whether a number is a prime or composite number.
```cpp
#include<iostream>
using namespace std;
class number
{
    int n,count=0,i;
    public:
    void input()
    {
        cout<<"enter a number:";
        cin>>n;
    }
    void output()
    {
        for(i=0;i<=n;i++)
        {
            if(n%2==0)
        {
            count++;
            break;
        }
        }
        if(count==2)
        {
            cout<<"the number is prime";
        }
        else
        {
            cout<<"the number is composite";
        }
    }
};
int main()
{
    number n1;
    n1.input();
    n1.output();
    return 0;
}
```
