#include <iostream>
using namespace std;


void a(int nu[2][5]);

void a(int nu[2][5]) {

  for(int n = 0; n < 2; n++)
    {
      for(int c =0; c < 3; c ++)
        {
          nu[n][c]*=2;
        }
    }
  
}



int main(void) {
  int num[2][3] = {{1,2,3},{1,6,3}};

  
  for (int n = 0; n < 2; n++) {
    for (int c = 0; c < 3; c++) {

      cout << num[n][c] << "\t";
    }
    cout << endl;
  }

 

  return 0;
}


