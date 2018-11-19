# Binary-to-Decimal
/* A C++ Program to convert a Binary digits into Decimal Number */
#include <iostream>
using namespace std;
int main()
{
	int n,i=1,sum=0,r,temp;
	cin >> n;
	while(n>0)
	{
	    r = n%10;
	    temp = r * i;
	    sum = sum + temp;
	    i=i*2;
	    n=n/10;
	}
    cout << sum  ;
}
