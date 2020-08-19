---
layout: post
title:  "Estructuras de repetición en c++"
date:   2020-08-16 21:35:56 -0500
tags: programación en c
logo: /dev-c.png
---

Una Estructura de Repetición en C++ le permite al programador especificar que se repita una acción
en tanto cierta condición se mantenga verdadera.

tenemos 3 estructuras:

while

La estructura de repetición While ejecuta un ciclo que se repetirá mientras que la condición sea verdadera.
Sintaxis while (<condición>) Ejemplo: while (a <= 10)

do/while

La estructura do/while es similar a la estructura while. En la while, la condición de continuación de ciclo se prueba al principio del ciclo,
antes de ejecutarse el cuerpo del mismo. La estructura do/while prueba la condición de continuación del ciclo repetitivo, después de ejecutar el cuerpo del ciclo,
por lo tanto, el cuerpo del ciclo repetitivo se ejecutará por lo menos una vez.
Sintaxis do Sentencias while (<condicion>); Ejemplo do { cout <<"entre la nota"; cin>>nota; i++; } while(i <=10);

for

La estructura de repetición for manera de manera automática todos los detalles de la repetición controlada por contador.
Sintaxis for (<inicio;final;contador>) Ejemplo: for(int i = 0;i <= 10;i++) cout <<”hola”;
