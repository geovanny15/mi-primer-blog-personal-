---
layout: post
title:  "Estructuras de control en C++"
date:   2020-08-16 21:35:56 -0500
tags: programación en c
---
las estructuras de control en c son aquellas que nos permiten ejecutar una o varias instrucciones dependiendo de la condición

*Estructura condicional:
en el caso de las estructuras condicionales Ejecuta una instrucción (o varias) dependiendo de si una condición es cierta o no.

IF ejecuta un bloque de sentencias sí o no

If-else ejecuta un bloque de sentencias entre dos opciones

Switch ejecuta un bloque de sentencias entre varias opciones

 #include <stdio.h>
 main(){int numero;printf("Introduce un entero: ");

 scanf("%d",&numero);

 if(numero < 0){numero = numero * (-1);
}

  printf("Su valor absoluto es: %d", numero);

}

cómo podemos observar ese pequeño ejemplo espero pueda servirte
para entender un poco sobre este bonito tema.
