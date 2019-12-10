#include <iostream>
  using namespace std;
  int main () {
  int m,n,c;
  cin >> m >> n;
  do {
  c=m%10;
  if (c==1 || c==5 || c==6 || c==0)
  cout << m << ' ';
  m++;
  }
  while (m!=n)
  return 0;
  }
