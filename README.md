#include<iostream>
using namespace std;
  int main()
  {
  int m,n;
  int sum=0;
  cin>>m;
  cin>>n;
  n= 100-n;
  while(m>0)
  {
  sum= sum+m;
  m= (m*n)/100;
  }
  cout<<sum;
  return 0;
  }
