
int main() {
    int n=5;
   int v[5] = {2,5,78,90,56};
   for(int i=0;i<n;i++)
   {
     cout<<v[i]<<endl;  
   
   }

    return 0;
}


//if im writing void to create a function then no need of writing return in tht ya toh voh return likn 
hai//


#include <iostream>
using namespace std;

void array(int v[], int n)  //esme hu, [] mention karte hai kyuki humme array kar ke indicate karna hai

{
    for (int i = 0; i < n; i++) {
        cout << v[i] << endl;
    }
}

int main() {
    int first[10] = {2, 5, 7, 9};  // Only first 4 values are set
    int a = 3;
    array(first, a);  // Should print: 2 5 7  // esme nhi likenge coz we already know
    return 0;
}
