### Operaciones Aritmeticas
Esto es muy sencillo. Comenzaremos por el ejemplo.

```java
int a = 4;
int b = 10;
int c = a+b;
```

Sabes que valor guarda c?. Así es, 14. Averigualo imprimiendo el valor en la salida estandar (http://monillo007.blogspot.com/2012/08/la-salida-de-datos-hacia-la-consola-en.html)

```java
System.out.println(c);
```

Hay operaciones que resultan en el redondeo entero. Mira el siguiente caso con atención
```java
double dnum = 5.5;
int num = dnum + 5;
System.out.println(num);
```
num será 10 y no 10.5

#Eligiendo tus variables
Hasta el momento conoces variables de tipo String, int y double para números no enteros.
Si quisieras calcular el promedio de 3 notas, eligirías probablemente tres double
```java
double nota1 = 10;
double nota2 = 13;
double nota3 = 14;
double promedio = (nota1+nota2+nota3)/3;
System.out.println(promedio);
```
Aquí tienes una lista más completa de tipos de variables que tienes en Java
http://www.learnjavaonline.org/en/Variables_and_Types

Usalas con sabiduría
