//1. Diseñar un algoritmo que imprima en la pantalla los primeros “n” múltiplos de 7 (positivos mayores que cero).

#include <iostream>
using namespace std;

int main() {
    int n, contador = 1, multiplos = 0;
    cout << "Ingrese la cantidad de multiplos de 7: ";
    cin >> n;

    while (multiplos < n) {
        if (contador % 7 == 0) {
            cout << contador << " ";
            multiplos++;
        }
        contador++;
    }
    return 0;
}
