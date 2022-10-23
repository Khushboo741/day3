# day3
#include <iostream>
using namespace std;
int main(){
int n,i,sum=0;
cout<<"enter value of n";
cin>>n;
i=1;

while(i<=n){
    if(i%2==0){
    sum=i+sum;
    }
i=i+1;
}

cout<<sum;

return 0;
}
