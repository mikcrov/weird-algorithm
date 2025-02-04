#include <iostream>
#include <string>
using namespace std;


int main() {
  int n;
  cout << "enter the number: ";
  cin >> n;
  cout << "\n" << n << "";


  while (n != 1) {
    if (n % 2 == 0) {
      n = n/2;
    }
    else if (n % 2 == 1) { //(kill azal)
      n = (3*n) + 1;
    }
    cout << n << " ";
  }
  return 0;
}
