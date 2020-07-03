# SLS-Lang
SLS-Lang es el lenguaje ideal si eres venezolano, pobre o si tenes de nombre sls. Este lenguaje esta programado en Python lo que lo hace de altisimo nivel, quiere decir que es un lenguaje a nivel nube.

# Features
- Print
- Formatos
- Variables
- Colorsitos corte samp
- Sockets para derribar a cualquier server de un solo pepaso
- Modulos

# Ejmplos
### module_one.sls
```c
print "Module 1"
```
### module_two.sls
```c
print "Module 2"
```
### test.sls
```c
// Modules
#include <./module_one.sls>
#include <./module_two.sls>

// Example print and comment
print "Hello, this is Cuarzo~n~This is new line~n~Colors: ~r~RED ~g~GREEN ~y~YELLOW ~b~BLUE ~m~MAGENTA ~c~CYAN ~w~WHITE ~n~"

// Variables example
new float:flotante = 1.5
new bool:boolean = True
new int:entero = 5

// Print valors
print "El valor de flotante es: ~c~{flotante}~w~"
print "El valor de boolean es: ~c~{boolean}~w~"
print "El valor de entero es: ~c~{entero}~w~"
```
