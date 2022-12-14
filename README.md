question : to print the sum of range
#include<iostream>
using namespace std;

int main()
{
int c, n;
cin >> c;
cin >> n;
int i, sum = 0;
for(i = c; i <= n; i++)
{
sum = sum + i;
}
cout << sum;
return 0;
}
