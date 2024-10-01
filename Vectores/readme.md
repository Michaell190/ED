# Titulo 1
## Titulo 2
### Titulo 3
#### Titulo 4
* uno
* dos
* tres
1. punto 1
2. punto 2
3. punto 3

**negritas**
_italica_

***negrita italica***
```C++
#include <iostream>
#include <limits>
#include <iomanip>
#include <locale>
using namespace std;

int main() {
//
    locale loc("");
    cout.imbue(loc);
    // 1. Entero (int)
    int numeroEntero = 42;
    cout << "Entero: " << numeroEntero << endl;
    cout << "Rango INT : " << numeric_limits<int>::min() << " a " << numeric_limits<int>::max();

    // 2. Entero corto (short int)
    short int numeroCorto = 32000;
    cout << "Entero corto: " << numeroCorto << endl;
    cout << "short int : " << numeric_limits<short int>::min() << " a " << numeric_limits<short int>::max();

![imagen](https://www.alfaromeousa.com/content/dam/alfa/cross/homepage/trim/trim-2023/AR-Trim-HP-Stelvio-Veloce%20Rossa-MCA.png)
