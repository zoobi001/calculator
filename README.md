its a simple calculator .
#include<iostream>
using namespace std ;
int main()
{
long int a ;
long int b;
long int c;
while(true)
{

char op ;
cout<< "enter a value of a :"<<endl ;
cin >> a ;
cout<< "enter a value of b :"<<endl ;
cin>> b ;
cout<< "enter operater value : "<<endl ;
cin>> op ;
if (op == '+')
{
	c = a + b ;
	cout<< "sum of values is "<<c<<endl ;
}
else if ( op =='-') 
{
 c = a - b ;
 cout<<"subtraction of values is"<< c<<endl ;
}
	else if (op == '*') 
{
	c = a * b ;
	cout <<"multiplication of values is"<<c<<endl ;
	
}
	else if(op=='/') 
	{
		c = a/b;
		cout<<"division of values is"<<c<<endl;
	}
else if  (op == '%')
{
	c = a% b ;
	cout<< "modulas of values is"<<c<<endl ;
	
}
   else 
   {

     cout<<"invalid operator:" ;
     break;
   }
}
return 0 ;
}
