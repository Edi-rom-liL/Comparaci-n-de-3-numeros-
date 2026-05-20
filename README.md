#include <iostream>

   using namespace std;

int main() {
    
    int a, b, c;
    
    cout << "Introduce el primer numero: ";
    cin >> a;
    cout << "Introduce el segundo numero: ";
    cin >> b;
    cout << "Introduce el tercer numero: ";
    cin >> c;

   
        if (a >= b && a >= c) {
        cout << "El numero mayor es: " << a << endl;
    }
    
        if (b >= a && b >= c) {
        cout << "El numero mayor es: " << b << endl;
    }
    
        if (c >= a && c >= b) {
        cout << "El numero mayor es: " << c << endl;
    }

    return 0;
}
