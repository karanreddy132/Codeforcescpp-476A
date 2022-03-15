# Codeforcescpp-476A
#include <bits/stdc++.h>
 
using namespace std;
 
int main(){
  int n,m;
  cin >> n >> m;
  if(m > n){
    cout << -1;
    return 0;
  }
  else{
    if((n%(2*m))==0){
      cout << m*(n/(2*m));
    }
    else{
      cout << m*((n/(2*m))+1);
    }
  }
  return 0;
}
