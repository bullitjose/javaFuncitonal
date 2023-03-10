# JAVA FUNCTIONAL PROGRAMMING

[youtube channel amigoscode, java functional programming](https://www.youtube.com/watch?v=VRpHdSFWGPs&ab_channel=Amigoscode)

> Java Util Function Package

[Package java.util.function java SE 17](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/function/package-summary.html)

+ Predicate
[Interface Predicate<T>](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/function/Predicate.html)

Predicate<T>  ->>>Represents a predicate (boolean-valued function) of one argument.

Function<T,R> ->>>Represents a function that accepts one argument and produces a result. Esto lo podemos aplicar a una funcion cualquiera, con un parametro y que produce un resultado
Ver: javaFuncional/src/main/java/functionalinterface/function
```
 Function<Integer, Integer> incrementByOneFunction= number ->number++;
 ```
 + Chaining functions
 
Combinar diferentes funciones.

```
static Function<Integer, Integer> incrementByOneFunction= number ->number+1;
