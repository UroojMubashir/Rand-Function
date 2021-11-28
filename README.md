
#include <iostream>
#include <array>
#include <algorithm>
using namespace std;

int main()
{
  int randomArry[10];
  for (int i=0; i<10; i++)
  {
      randomArry[i]=rand()%50;
      cout<<randomArry[i]<<endl;
  }
}
