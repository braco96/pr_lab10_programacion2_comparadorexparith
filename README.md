# PR_LAB11_PROGRAMACION2_COMPARADOREXPARITH
**Autor:** Luis Bravo  
**Curso:** 2017–2018  
**Asignatura:** Programación II — Laboratorio 11 (A.E.D.)

## Descripción
Este laboratorio implementa un comparador de árboles binarios que representan expresiones aritméticas sobre enteros.  
El comparador evalúa los árboles con un método auxiliar `eval()` y devuelve un valor entero según la relación entre ambas expresiones.

## Métodos principales
- `compare(a1, a2)`  
- `eval(arbol)` — Devuelve el valor numérico de una expresión aritmética.

## Casos especiales tratados
- Árbol `null` o vacío → `IllegalArgumentException`
- Enteros no en hojas → `RuntimeException`
- Operadores binarios sin ambos hijos → `RuntimeException`
- División con denominador 0 → `RuntimeException`
- Operadores unarios con 0 o 2 hijos → `RuntimeException`

## Ejecución
```bash
javac -cp . ComparadorExpArith.java Tester.java
java -cp . Tester
```

## Archivos incluidos
- `ComparadorExpArith.java`  
- `ElementoExpresion.java`  
- `TipoExpresion.java`  
- `Tester.java`  
- `guia.pdf`  
- `.project`, `.classpath`, `pom.xml`

## Autor
— *Luis Bravo*
