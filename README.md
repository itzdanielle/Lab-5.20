# Lab-5.20
#include <iostream>
using namespace std;

int main() {
  double raduis;
  double volume;
  const double PI = 3.14; 
  
  cout << "Input the value of the raduis\n";
  cin >> raduis; 

  volume = 4.0/3.0 * PI * (raduis * raduis * raduis);
  cout << "The volume is: " << volume << endl; 
  



}
