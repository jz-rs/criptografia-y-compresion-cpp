# Criptografía y Compresión en C++

![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white&style=flat-square)
![Consola](https://img.shields.io/badge/App-Consola-4D4D4D?logo=windowsterminal&logoColor=white&style=flat-square)
![Windows](https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white&style=flat-square)
![Cifrado](https://img.shields.io/badge/Cifrado-cl%C3%A1sico-6A1B9A?style=flat-square)
![Compresión](https://img.shields.io/badge/Compresi%C3%B3n-Huffman%20%7C%20LZW-2E7D32?style=flat-square)
![Búsqueda](https://img.shields.io/badge/B%C3%BAsqueda-KMP-F57C00?style=flat-square)

Aplicación de consola en C++ que reúne algoritmos clásicos de **búsqueda de patrones, cifrado y compresión de texto**. Se elige el algoritmo desde un menú interactivo, se ingresa un texto y el programa muestra el resultado.

## Algoritmos incluidos

| Categoría | Algoritmos |
|---|---|
| Búsqueda de patrones | Fuerza bruta, KMP (Knuth–Morris–Pratt) |
| Compresión | Huffman, LZW |
| Cifrado clásico | César (cifrar y descifrar), Afín, Vigenère, Playfair, Hill |

Cada algoritmo está implementado en su propia función y se accede desde el menú principal.

## Menú

```
1) Fuerza Bruta
2) KMP
3) ZLW
4) Afin
5) Cesar
6) PLAYFAIR
7) Huffman
8) Vigenere
9) Hill
0) Salir
```

## Cómo ejecutarlo

Está pensado para Windows (usa `conio.h` y `windows.h`).

1. Compilar:

```
g++ criptografia-y-seguridad-cpp.cpp -o crypto
```

2. Correr el ejecutable:

```
.\crypto
```

3. Elegir un algoritmo del menú e ingresar el texto a procesar.

## Tecnologías

* C++
* Manejo de cadenas
* Árboles binarios (Huffman)
* Estructuras de datos: `vector`, `unordered_map`, `queue`
* Modularidad con funciones

## Qué practiqué

* Compresión y descompresión de texto
* Cifrado clásico
* Búsqueda y coincidencia de patrones
* Algoritmos fundamentales de seguridad y compresión
* Estructuras de datos y funciones en C++
