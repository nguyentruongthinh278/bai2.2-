#include<iostream>
using namespace std;
int main()
{
  int n;
  float p = 1;
  do
  {
    cout<<"\nNhập vào số n: ";
    cin>>n;
    if(n < 1)
      {
      cout<<"\nSố n phải lớn hơn hoặc bằng 1, vui lòng nhập lại !";
      }
  }while(n < 1);
 
  for(int i = 1; i <= n; i++){
    p = p * i;
  }
  
  while(i <= n)
 {
   p = p * i;
     i++;
  }
  cout<<"\n Tích 1 x 2 x ... x "<<n<< " là: " << p;
}
