# Programación básica

## Universidad Autónoma de Nuevo León
## Facultad de Ciencias Físico Matemáticas
## Multimedia y Animación Digital

### Alberto Benavides
### Agosto a diciembre 2018

## Historia [*](https://www.veracode.com/blog/2013/04/the-history-of-programming-languages-infographic)

Año | Lenguaje(s) | Usos
:---:|---|:---:
1957 - 1959 | Fortran, LISP, COBOL |<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/NASA_logo.svg/1200px-NASA_logo.svg.png" width="70px"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d2/Circle-icons-creditcard.svg/1024px-Circle-icons-creditcard.svg.png" width="60px"> |
1970 | PASCAL | <img src="https://cdn.freebiesupply.com/logos/large/2x/skype-3-logo-png-transparent.png" width="50px"> |
1972 | C | <img src="https://upload.wikimedia.org/wikipedia/commons/c/c2/Unix_Logo.gif" width="80px">
1983 | C++ | <img src="https://i2.wp.com/www.ucreative.com/wp-content/uploads/2015/10/Adobe-Large.png" width="100px"> <img src="https://image.flaticon.com/icons/png/512/220/220218.png" width="50px">
1983 | Objective-C | <img src="https://image.freepik.com/free-icon/apple-logo_318-40184.jpg" width="50px">
1987 | PERL | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Amazon_logo_plain.svg/1024px-Amazon_logo_plain.svg.png" width="100px">
1991 | Python | <img src="http://diylogodesigns.com/blog/wp-content/uploads/2016/04/google-logo-icon-PNG-Transparent-Background.png" width="50px"> <img src="https://vignette.wikia.nocookie.net/logopedia/images/7/72/Yahoo%21_1_Favicon.svg/revision/latest?cb=20130807230312" width="70px"> <img src="https://cdn.freebiesupply.com/logos/large/2x/spotify-2-logo-png-transparent.png" width="50px">
1993 | Ruby | <img src="https://logosmarcas.com/wp-content/uploads/2018/05/Twitter-logo.png" width="70px">
1995 | Java | <img src="https://images.vexels.com/media/users/3/139556/isolated/preview/1718a076e29822051df8bcf8b5ce1124-logo-de-android-by-vexels.png" width="70px">
1995 | PHP | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Facebook_logo_%28square%29.png/600px-Facebook_logo_%28square%29.png" width="50px"> <img src="https://s.w.org/style/images/about/WordPress-logotype-wmark.png" width="60px">
1995 | Javascript | <img src="https://www.mobileworld.it/wp-content/uploads/2017/06/gmail-final.png" width="50px"> <img src="https://cdn.freebiesupply.com/logos/large/2x/mozilla-firefox-1-logo-png-transparent.png" width="50px">

## Índice TIOBE 2018 (popularidad) [*](https://www.tiobe.com/tiobe-index/)

Puesto | Lenguaje | Índice (%)
--- | --- | ---:
1 | Java | 16.88
2 | C | 14.97
3 | C++ | 7.47
4 | Python | 6.99

## Definición

* Representación simbólica para el conteo de elementos en un conjunto (cardinalidad).
* Tiene $n$ símbolos sucesivos que aumentan de $n$ en $n$.


## Ejemplo: Sistema numérico decimal
$A = \{0, 1, 2, 3, 4, 5, 6, 7, 8, 9\}$

Libretas | Acumulado |  | Libretas | Acumulado
:---:|---: | :---: | :---: | ---:
| | 0 | | :ledger: | 6
:ledger: | 1 || :ledger: | 7
:ledger: | 2 || :ledger: | 8
:ledger: | 3 || :ledger: | 9
:ledger: | 4 || :ledger: | **10**
:ledger: | 5 || :ledger: | **11**


## Sistemas numéricos computacionales

* Binario: 

$$B = \{0, 1\}$$

* Decimal:  

$$D = \{0, 1, 2, 3, 4, 5, 6, 7, 8, 9\}$$

* Hexadecimal: 

  $$H = \{0, 1, 2, 3, 4, 5, 6,7, 8, 9, A, B, C, D, E, F\}$$


## Equivalencias entre sistemas

Decimal | Binario | Hexadecimal
---: | ---: | ---:
0 | 0 | 0
1 | 1 | 1
2 | :question: | 2
3 | 11 | 3 
10 | :question: | A
11 | 1011 | :question:
16 | :question: | :question:
  

## Conversión

* Binario a decimal
$$1010_2 = 1 \times 2^3 + 0 \times 2^2 + 1 \times 2^1 + 0 \times 2^0$$
* Hexadecimal a decimal
$$\text{DA} 5_{16} = 13 \times 16^2 + 10 \times 16^1 + 5 \times 16^0$$
* Hexadecimal a binario
$$\text{DA} 5_{16} = 1101 \ 0110 \ 0101 _2$$
* Binario a hexadecimal
$$101110_2 = 0010 \ 1110_2 = 2\text{E}_{16}$$


## Decimal a binario 

$$28_{10} = 11100_2$$
* Dividir entre 2 los factores resultantes hasta llegar a $2$ o $1$.
* Almacenar los residuos.

Factor | Residuo
--- | :---:
$28 / 2$ | 0
$14 / 2$ | 0
$7 / 2$ | 1
$3 / 2$ | 1
$1$ | $1$


## Crear un proyecto en Visual Studio 2017

1. Abrir VS2017
2. Archivo > Nuevo > Proyecto
3. Elegir Visual C++ (columna izquierda)
4. Elegir Proyecto vacío
5. Especificar nombre y ubicación
6. Aceptar


## Crear archivos dentro de un proyecto de VS2017

1. Abrir Explorador de soluciones
	* Pestaña derecha
	* Ver > Explorador de soluciones
2. Clic derecho en el nombre de la solución (negritas)
3. Agregar > Nuevo elemento...
4. Archivo `.cpp`
5. Especificar nombre
	* Sin espacios
	* Sin caracteres especiales: [áèïñ?~...]
7. Agregar


## Ejemplos minimalistas

```cpp
#include <iostream>
int main(){
  sdt::cout << "Hola mundo.";
  return 0;
}
```

```cpp
#include <iostream>
using namespace std;

int main(){
  cout << "Hola mundo.";
  return 0;
}
```

```cpp
getchar(); // Pausa la ejecución a la espera de <Enter>
```

* ¿Cuándo va el punto y coma al final?


## Argumentos de `main` [*](http://www.cplusplus.com/articles/DEN36Up4/)

```cpp
#include <iostream>
using namespace std;

int main(int argc, char* argv[]){
  // Los argv son cadenas de texto (char[])  
  for (int i = 0; i < argc; i++){
  	cout << argv[i] << endl;
  }
  
  return 0;
}

```


## Ejecutar códigos C++ desde consola (opcional)
* MinGW
	* [Instalación](https://www.fdi.ucm.es/profesor/luis/fp/devtools/MinGW.html)
	* [Uso](https://www.fdi.ucm.es/profesor/luis/fp/devtools/MinGWUso.html)

```
rem Generar un ejecutable de un código C++
g++ archivo.cpp -o ejecutable.exe

rem Correr el ejecutable
ejecutable
ejecutable.exe

rem Correr el ejecutable con argumentos (argvs)
ejecutable argumento1 argumento2 ...
```


## Ejecutar un programa en VS2017

1. Guardar:heavy_exclamation_mark::heavy_exclamation_mark::heavy_exclamation_mark:
	* ¿Ya guardaste?
	* Puedes usar `Ctrl + S` para guardar
2. ¿Errores? :beetle: Corrígelos.
4. Depurar:
	* Depurar > Iniciar depuración
	* Clic en <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRbWxJFz-RBpyLWph8DVof9lVPe72ZBf2V7iOdpnjoZg9iN6KLB" width="30px">
	* Pulsar `F5`


## Entrada y salida de flujos: `iostream`

```cpp
cout << "Muestra en la consola (output)" << endl;

int n; // Se declara un entero llamado n
cin >> n; // Guarda la entrada de consola en n

char s[10]; // Se declara un arreglo de 10 caracteres
cin >> s; // Guarda la entrada de consola en s

// Muestra n y s en consola
cout << n << s << endl;
```

## Definición de tipos de datos

* Reservan espacio en memoria
* Son diferentes
	* Información que almacenan
	* Rangos de valores válidos
* Se asignan a **variables**

```cpp
tipoDeDato nombreDeLaVariable;
```


## Repaso tipos de datos

```cpp
int entero;
entero = 4;

char caracter;
caracter = 'a'; // ¡Comillas simples!

char cadena[10];
// cadena = "hola"; // Da error
cin >> cadena;

// Variable vacía para funciones sin valor de retorno
void main(){}
```


## Tipos de datos

```cpp
long enteroLargo;

float flotante;
flotante = 1.0f; // Se debe incluir f al final
flotante = 1; 

double flotanteLargo;

bool booleana;
booleana = true;
booleana = false;
```


## Cadenas de caracteres

```cpp
#include <string>
[...]
string cadenaPlus;
cadenaPlus = "¡No hace falta especificar longitud!";

// Obtener la línea de entrada (con espacios incluidos)
getline(cin, cadenaPlus); 
```
Solucionar problema de compilación con g++ [ * ](https://stackoverflow.com/questions/42645527/c-mingw-linker-error-znst7-cxx1112basic-stringlcst11char-traitslcesalcee10-m)


## Conversión entre tipos de datos [ * ](https://stackoverflow.com/questions/5590381/easiest-way-to-convert-int-to-string-in-c)

```cpp
// char[] to int
int i = atoi("1234");

// string to int
int i = stoi("1234");
```

```cpp
#include <string>
[...]

// Valor numérico a cadena
string n = to_string(1234);
string f = to_string(12.34f);
```


## Operadores aritméticos para enteros

```cpp
int a = 3;
int b = 2;
int c;

// Igualdad (asignación)
c = a; // c = b;

// Suma
c = a + b; // Equivalente: b + a;

// Resta
c = a - b; // No equivalente: b - a;

// Multiplicación
c = a * b; // Equivalente: b * a;

// División
c = a / b; // No equivalente: b / a;
```


## Operadores para enteros

```cpp
int a = 3;
int b = 2;
int c;

// Asignación = Actualización
a = a + a;

b = b + a;

// Orden de operaciones
c = a * b + a / b + (2 + 3 * b - (5 / 2) % 4) + 5 * b;

// Módulo (residuo)
c = a % b; // ¿Valor?
c = b % a; // ¿Valor?

// ¿Cómo saber si un número es par?
```


## Operadores compuestos para enteros

```cpp
int a = 3;
int b = 5;

a += b; // Equivalente: a = a + b;
a -= b; // Equivalente: a = a - b;
a *= b; // Equivalente: a = a * b;
a /= b; // Equivalente: a = a / b;

a++; // Equivalente: a = a + 1;
b--; // Equivalente: b = b - 1;

// ¿Cuánto vale a, b?
a = b++;
b = ++a;
```


## Ley de los exponentes y librería [`math.h`](http://www.cplusplus.com/reference/cmath/)

* Los operadores aritméticos de enteros también pueden aplicarse a flotantes

```cpp
float a = 3;

// ¿Cómo elevar al cuadrado a?

// ¿Cómo elevar al cubo a?
```

```cpp
#include <math.h>
[...]
float a = pow(3, 2); // Equivalente: 3 ^ 2

// Cómo obtener una raíz
a = sqrt(9);
```


## Redondeo y valor absoluto

```cpp
#include <math.h>
[...]

float a = 3.5f;
float b = 3.4f;
float c = -3.4f;

// Redondeo al más cercano
a = round(a);

// Función suelo: Redondeo al entero menor
b = floor(a);

// Función techo: Redondeo al entero mayor
c = ceil(a);

// Valor absoluto
c = abs(c);
```


## Trigonometría

```cpp
#include <math.h>
[...]

float a = 60;

// Seno en radianes
float seno = sin(a);

// Coseno en radianes
float coseno = cos(a);

// Tangente en radianes
float tangente = tan(a);

float a = 60;

// Seno inverso en radianes
float senoInverso = asin(a);

// Coseno inverso en radianes
float coseno = acos(a);

// Tangente inversa en radianes
float tangenteInversa = atan(a);
```


## Operadores relacionales

```cpp
bool resultado;

resultado = 3 < 4; // Menor que

resultado = 3 > 4; // Mayor que

resultado = 3 <= 4; // Menor o igual que 

resultado = 3 >= 4; // Mayor o igual que

resultado = 3 == 4; // Igual que

resultado = 3 != 4; // Distinto que
```


## Operadores lógicos

```cpp
bool v = true; // 1

bool f = false; // 0


bool resultado;


resultado = v && f;

resultado = v || f;


cin >> resultado; // Lee 1 o 0 (true, false)
```


## Bits y bytes. Unidades computacionales

* $1 \text{ bit}$: Puede tomar como valor $0$ o $1$
* $1 \text{ byte } (\text{B})$: 
	* Comprende $8 \text{ bit}$ de información
	* Puede tomar valores desde $[0, 11111111] \text{ bit}$

¿Cuántos valores permite representar un $\text{byte}$?


## `sizeof()`

Regresa la cantidad de bytes que ocupa una variable o tipo de dato

```cpp
sizeof(char);

sizeof(int);

sizeof(float);

// Por ejemplo:
int conjunto[] = {0, 1, 2, 3, 4};

int cardinalidad = sizeof(conjunto) / sizeof(conjunto[0]);
```


## [Tamaño de tipos de datos](https://www.geeksforgeeks.org/c-data-types/)

Tipo de dato | Tamaño (bytes) | Rango de valores
:--- | --: | --:
`char` | 1 | $[0, 255]$
`int` | 4 | $[\pm 2\ 147\ 483\ 647]$
`unsigned int` | 4 | $[0, 4\ 294\ 967\ 295]$
`float` | 4 | $[\pm 3.4 \times 10^{\pm38}]$
`double` | 8 | $[\pm 1.7 \times 10 ^{\pm 308}]$


### [`char` y American Std Code for Information Interchange](https://ascii.cl/)

ASCII | Símbolo | | ASCII | Símbolo
:--:|:--:|---|:--:|:--:
48 | 0 | | 65 | A
49 | 1 | | 66 | B
50 | 2 | | ... | ...
51 | 3 | | 89 | Y
52 | 4 | | 90 | Z
53 | 5 | | 97 | a
54 | 6 | | 98 | b
55 | 7 | | ... | ...
56 | 8 | | 121 | y
57 | 9 | | 122 | z


## [`string`](http://www.cplusplus.com/reference/string/string/)

```cpp
#include <iostream>
#include <string>
using namespace std;
[...]

string a = "hola";
cout << a.at(0) << a.at(2);
```
Salida:
```
hl
```


## Breakpoints

* Puntos de interrupción 
* Pausan la ejecución de un programa en una línea
* Permiten:
	* Inspeccionar variables
	* Encontrar errores
* Añadir y eliminar breakpoints
	* Pulsar `f9` en la línea deseada
	* Dar clic sobre la columna a la izquierda del número de línea en la columna deseada


## Opciones tras pausa

* Variables locales
	* Pestaña inferior
	* Depurar > Ventanas > Variables locales
* Inspección
	* Pestaña inferior
	* Depurar > Ventanas > Inspección > Inspección [1-4]
* Continuar (botón Play)
* Detener depuración (Botón Stop)
* Avanzar a la siguiente línea `f10`


## Estructura

```cpp
bool cond1 = true;
bool cond2 = false;

if(cond1){
  // Se cumple la condición 1
} else if(cond2){
  // Se cumple la condición 2
} else{
  // No se cumple ninguna de las condiciones anteriores
}
```


## Variables globales

* Variables que pueden usarse en cualquier función
* Se declaran fuera de cualquier función
* Variables **locales** sólo existen dentro de la función donde se declaran

<hr>

```cpp
system("cls"); // Limpia el contenido de la pantalla
```


## Estructura con `char`

```cpp
char c;

cin >> c;

switch (c)
{  
  case 'A':
    cout << "Elegiste A" << endl;
    break;
  case 'B':
    cout << "Elegiste B" << endl;
    cout << "y le sigue a C" << endl;
  case 'C':
    cout << "Elegiste C" << endl;
    break;
  default:
    cout << "Equivalente al else" << endl;
    break;
}  
```


## Estructura con `int`

```cpp
int c;

cin >> c;

switch (c)
{  
  case 1:
    cout << "Elegiste 1" << endl;
    break;
  case 2:
    cout << "Elegiste 2" << endl;
    cout << "y le sigue 3" << endl;
  case 3:
    cout << "Elegiste 3" << endl;
    break;
  default:
    cout << "Equivalente al else" << endl;
    break;
}  
```


# Operador `?`

```cpp
int a = 1;
int b = 2;
int c = 0;

if (a == b){
  c = a + b;
}

// Es lo mismo que:
c = (a == b) ? (a + b) : c;
```


## Arreglos vacíos

```cpp
int enteros[5];

char caracteres[5];

float flotantes[5];

bool booleanos[5];
```

## Elementos de los arreglos

```cpp
int enteros[] = {1, 2, 3, 4, 5};

char caracteres[] = {'a', 'b', 'c', 'd', 'e'};

float flotantes[] = {1.0, 2.0, 3.0, 4.0, 5.0};

bool booleanos[] = {true, false, true, false, true};
```


## Obtener elementos de un arreglo

```cpp
int entero1 = enteros[0];
int entero2 = enteros[1];
// ...

char caracter1 = caracteres[0];
char caracter2 = caracteres[1];
// ...

float flotante1 = flotantes[0];
float flotante2 = flotantes[1];
// ...

bool booleano1 = booleanos[0];
bool booleano2 = booleanos[1];
// ...
```


## Establecer elementos de un arreglo

```cpp
enteros[0] = 1;

caracteres[0] = 1; // Correspondiente al ASCII 1

flotantes[0] = 1; // Equivalente a 1.0

booleanos[0] = 1; // Equivalente a true
```


## Tamaño de arreglos

```cpp
int a = 0;

// Devuelve el tamaño en bytes de variable a
sizeof(a); // 4 bytes

int arreglo[10];
sizeof(arreglo); // Devuelve 40 bytes

int alumnos[] ={
  // muchos alumnos
}

// Cantidad de alumnos = peso de todos / peso de cada uno
int cardinalidad = sizeof(alumnos) / sizeof(alumnos[0])
```



## Arreglos mulidimensionales

```cpp
int unidimensional[15];

// es equivalente a

int bidimensional[5][3];

```


## Arreglos bidimensionales

```cpp
// [...]
#include <string>

// [...]

bool b[3][4];

char c[3][4];

int i[3][4];

float f[3][4];

string s[3][4];
```

## `struct`

* Agrupación de tipos de datos bajo un mismo nombre
* Los tipos de datos pueden tener diferente nombre y capacidad


## Estructura básica

```cpp
struct nombreStruct{ // Declaración
  tipoDato1 nombre1;
  tipoDato2 nombre2;
}; // ¡Ojo con este punto y coma!

// Creación de una instancia de la estructura
nombreStruct instancia;
```


## Arreglos de estructuras

```cpp
struct objeto{
  string nombre;
  string desc;
  float precio;
  int atk;
  int def;
};

objeto inventario[100];
inventario[0].nombre = "Excalibur";
inventario[0].desc = "Espada del Rey Arturo";
inventario[0].precio = INFINITY; // De la librería math.h
inventario[0].atk = 10;
inventario[0].def = 2;
```


Estructuras anidadas

```cpp
struct jugador{
  string nombre;
  int vidas;
  float estamina;
  objeto inventario[100];
};

jugador j1;
j1.nombre = "Arturo";
j1.vidas = 3;
j1.estamina = 100.0;

j1.inventario[0].nombre = "Excalibur";
j1.inventario[0].desc = "Espada del Rey Arturo";
j1.inventario[0].precio = INFINITY;
j1.inventario[0].atk = 10;
j1.inventario[0].def = 2;
```


## Ciclo `for`

```cpp
// Estructura básica
for(/*iterador*/; /*condición*/; /*incremento*/){
  // Código
}
```

```cpp
// Ejemplo
for (int i = 0; i < 3; i++){
  cout << i << endl;
}
```
Salida:
```bash
0
1
2
```


## Tradución del ejemplo

```cpp
for (int i = 0; i < fin; i++){
  cout << i << endl;
}
```
1. Desde $i = 0$
2. Si $i < 3$:
   3. Imprimir $i$
   4. Incrementar $i$ en $1$
5. Volver a 2.


## Ciclo del ejemplo

```cpp
for (int i = 0; i < fin; i++){
  cout << i << endl;
}
```
1. $i = 0$.
2. Como $i < 3$, se imprime $i$ (`0`).
3. Se incrementa en $1 \Longrightarrow i = 1$.
4. Como $i < 3$, se imprime $i$ (`1`).
5. Se incrementa en $1 \Longrightarrow i = 2$.
6. Como $i < 3$, se imprime $i$ (`2`).
7. Se incrementa en $1 \Longrightarrow i = 3$
8. Como $i \nless 3$, se sale del ciclo.


## Variaciones del mismo ejemplo

```cpp
// Menor o igual
for (int i = 0; i <= 2; i++){
  cout << i << endl;
}

// Doble incremento
for (int i = 0; i < 6; i += 2){
  cout << (i / 2) << endl;
}

// ¡Al revés!
for (int i = 3; i > 0; i--){
  cout << (3 - i) << endl;
}
```


## `break` :star:

```cpp
for (int i = 0; i < 10; i++){
  if(i == 5){ // Si i es 5
    break; // se corta el ciclo
  }
  cout << i << endl;
}
```

Salida:
```bash
0
1
2
3
4
```


## Equivalente del ejemplo `break`

```cpp
for (int i = 0; i < 10; i++){
  if(i < 5){
    cout << i << endl;
  }
}

// Otro
for (int i = 0; i < 5; i++){
  cout << i << endl;
}
```

Salida:
```bash
0
1
2
3
4
```


## `continue` :star:

```cpp
for (int i = 0; i < 10; i++){
  if(i == 5){ // Si i es 5
    continue; // se salta esta iteración
  }
  cout << i << endl;
}
```

Salida:
```bash
0
1
2
3
4
6
7
8
9
```


## Equivalente del ejemplo `continue`

```cpp
for (int i = 0; i < 10; i++){
  if(i != 5){
    cout << i << endl;
  }
  
}
```

Salida:
```bash
0
1
2
3
4
6
7
8
9
```


## Ciclo `while`

```cpp
// Estructura básica
while(/*condición*/){
  // Código
}
```

```cpp
// Ejemplo
int i = 0;
while (i < 3){
  cout << i << endl;
  i++;
}
```
Salida:
```bash
0
1
2
```


## Ciclo `do`, `while`

```cpp
// Estructura básica
do{
  // Código
}
while(/*condición*/);
```

```cpp
// Ejemplo
int i = 0;
do{
  cout << i << endl;
  i++;
}
while (i < 3);
```


## `break` :star:

```cpp
while (i < 10){
  if(i == 5){ // Si i es 5
    break; // se corta el ciclo
  }
  cout << i << endl;
  i++;
}
```

Salida:
```bash
0
1
2
3
4
```


## `continue` :star:

```cpp
while (i < 10){
  if(i == 5){ // Si i es 5
    continue; // se salta esta iteración
  }
  cout << i << endl;
  i++;
}
```

Salida:
```bash
0
1
2
3
4
6
7
8
9
```


## Estructura de un ciclo anidado

```cpp
for (int i = 0; i < 3; i++){
  for (int j = 0; j < 3; j++){
  /* Código */
  }
}
```

# 25. Funciones


## Definición

* Estructura de código 
* Realiza tareas individualmente

```cpp
// Estructura general

tipoDato1 nombreFuncion(tipoDato2 parámetro1 /* ... */){
  /* Código */
}
```


## Casos

```cpp
void Saludo1(){ // Sin retorno ni parámetros
  cout << "Hola." << endl;
}
Saludo1();

void Saludo2(string s){ // Sin retorno, con parámetro
  cout << s << endl;
}
Saludo2("Hola.");

string Saludo3(){ // Con retorno, sin parámetro
  return "Hola.";
}
cout << Saludo3() << endl;

string Saludo4(string s){ // Con retorno y parámetro
  return s + ", chicos.";
}
cout << Saludo4("Hola") << end;
```


## Parámetros

```cpp
void func (int a){ // Existen en el contexto de la función
  a = a + 3;
}
void main(){
  a; // Usar a aquí marcaría error
}

int pot(int a){ // Pueden nombrarse como variables externas
  return a * a;
}
void main(){
  int a = 3;
  cout << Cuadrado(a) << endl;
  cout << a << endl; // Pero no son lo mismo
}

```

# 26. Funciones recursivas


## Estructura básica

```cpp
void recursiva(){
  recursiva(); // Función que se llama a sí misma
}

void main(){
  recursiva(); // Manda llamar a la función recursiva
}
```


## Programa de ejemplo de escritura

```cpp
#include <iostream>
#include <fstream>
using namespace std;

int main () {
  ofstream archivo; // Se crea objeto de escritura
  archivo.open ("ejemplo.txt"); // Se especifica archivo
  archivo << "Se escribe como en consola.\n";
  
  // Al terminar se cierra (esto guarda el contenido)
  archivo.close(); 
  
  return 0;
}
```


## Programa de ejemplo de lectura

```cpp
#include <iostream>
#include <fstream>
#include <string>
using namespace std;
int main () {
  string l;
  // Se crea un objeto del archivo
  ifstream archivo ("ejemplo.txt");
  
  if (archivo.is_open()){ // Si sepudo abrir
    while (getline(archivo, l)){ // Mientras se pueda leer
      cout << l << '\n'; // Se imprime línea por línea
    } // Al terminar de leer las líneas
    archivo.close(); // Se cierra el archivo
  }
  else{ // Si no se pudo abrir
    cout << "No se pudo abrir el archivo."; 
  }
  return 0;
}
```


## Tipos de maneras de guardar archivos

Parámetro | Operación
:--|:--
`ios::in` | Lectura.
`ios::out` | Escritura.
`ios::binary` | Modo binario.
`ios::ate` | Posición inicial al final del archivo.
`ios::app` | Abre al final del archivo.
`ios::trunc` | Si el archivo existe, borra el contenido.


## Clases de manejo de archivos

Clase | Parámetro por defecto
:-- | :--
`ofstream` | `ios::out`
`ifstream` | `ios::in`
`fstream` | `ios::in | ios::out`


```cpp
ofstream nombre ("destino.txt", ios::out);
ifstream nombre ("destino.txt", ios::in);
fstream nombre ("destino.txt", ios::in | ios::out);
```

# 32. Lectura y escritura de estructuras


## Requisitos

1. Crear una estructura

```cpp
struct estructura{
  int i;
  string s;
};
```

2. Declarar un arreglo de estructuras

```cpp
estructura ejemplo[100];
```


## Guardar

```cpp
// Se crea objeto de escritura
ofstream archivo; 

// Se guarda como binario
archivo.open("ejemplo.data", ios::binary);

// Se escribe el arreglo entero en el archivo
archivo.write((char*)&ejemplo, sizeof(ejemplo));

// Al terminar se cierra el archivo
archivo.close();
```


## Leer

```cpp
// Crear objeto de lectura
ifstream archivo("ejemplo.data", ios::binary);

// Leer el archivo
archivo.read((char*)&p, sizeof(p));

// Cerrar el archivo
archivo.close();
```


## Definición de puntero

* Variable que almacena dirección de memoria de otra variable
* Utiliza operadores:
	* `&`: Dirección (ubicación)
	* `*`: Recuperador de la variable

```cpp
tipoDato *puntero; // Declaración de puntero
tipoDato variable = valor; // Definición de variable

puntero = &variable; // Guarda dirección
*puntero == variable; // Equivalentes
```


## [Ejemplo `&`](http://www.cplusplus.com/doc/tutorial/pointers/)

```cpp
myvar = 25;
foo = &myvar;
bar = myvar;
```

<center><img src=http://www.cplusplus.com/doc/tutorial/pointers/reference_operator.png></center>


## [Ejemplo `*`](http://www.cplusplus.com/doc/tutorial/pointers/)

```cpp
baz = *foo;
```

<center><img src=http://www.cplusplus.com/doc/tutorial/pointers/dereference_operator.png></center>


## Tipo de datos de un puntero

* Una variable necesita un tipo de dato
* Un tipo de dato tiene un tamaño específico en bits
* Un puntero apunta a una dirección de memoria de un tipo de dato
* Un puntero debe ser del tipo de dato del valor que recupearará


## Ejemplo I

```cpp
#include <iostream>

int main(){
  int valor = 3;
  int *punteroE = &valor;
  
  cout << punteroE == valor << endl;
  cout << *punteroE == valor << endl;
  cout << punteroE == &valor << endl;
  cout << *punteroE == &valor << endl;

  return 0;
}
```


## Ejemplo II

```cpp
#include <iostream>

int main(){
  int a = 2;
  int b = 3;
  int *A, *B, *C;
  
  A = &a;
  B = &b;
  cout << *A << endl;
  cout << *B << endl;
  
  *C = *A;
  cout << *C << endl;
  
  C = B;
  cout << *C << endl;

  return 0;
}
```


# Fuentes
* http://www.uacj.mx/CGTI/CDTE/JPM/Documents/IIT/sistemas_numericos/conversiones/sistemas-numericos.html
* https://www.tutorialspoint.com/cplusplus/index.htm
* http://www.cplusplus.com/doc/tutorial/
* https://www.tutorialspoint.com/cplusplus/cpp_variable_types.htm
* http://www.cplusplus.com/doc/tutorial/variables/
* http://www.cplusplus.com/doc/tutorial/operators/
* http://www.cplusplus.com/doc/tutorial/operators/
* http://www.cplusplus.com/reference/cmath/
* https://docs.microsoft.com/en-us/visualstudio/debugger/using-breakpoints
* https://www.learncpp.com/cpp-tutorial/42-global-variables/
* http://www.cplusplus.com/doc/tutorial/functions/
* https://en.cppreference.com/w/cpp/language/switch
* http://www.cplusplus.com/doc/tutorial/arrays/
* http://www.cplusplus.com/doc/tutorial/structures/
* https://www.tutorialspoint.com/cplusplus/cpp_for_loop.htm
* http://www.cplusplus.com/doc/tutorial/functions/
* http://www.cplusplus.com/doc/tutorial/files/
* https://stackoverflow.com/a/5506657
* http://www.cplusplus.com/doc/tutorial/pointers/