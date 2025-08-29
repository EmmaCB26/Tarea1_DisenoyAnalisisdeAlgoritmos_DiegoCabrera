Suma de Pares con Valor K

Esta aplicación en Java permite determinar si existe un par de números dentro de un arreglo que sumen un valor específico K. Se implementan distintos enfoques para comparar eficiencia y estructura.

Funcionalidades

- Solicita al usuario el tamaño del arreglo, los valores y el número objetivo K.
- Permite elegir entre tres métodos de resolución:
  - Método clásico con doble ciclo for.
  - Método modular usando una clase externa (SumaArreglos).
  - Método eficiente con diccionario hash (SolucionHash).

Algoritmos implementados

- Fuerza bruta (O(n²)): compara todos los pares posibles.
- HashSet (O(n)): guarda los elementos vistos y busca el complemento en tiempo constante.
- Modularización: separa la lógica en clases para aplicar principios de encapsulamiento.

Cómo ejecutar

1. Compila el archivo principal:
   javac Main.java
2. Ejecuta el programa:
   java Main
3. Ingresa los datos solicitados y selecciona el método que deseas probar.

Archivos recomendados

- Main.java: punto de entrada y menú de opciones.
- SumaArreglos.java: clase modular con método clásico.
- SolucionHash.java: clase con método eficiente usando diccionario hash.

Ideal para

- Estudiantes de Diseño y Análisis de Algoritmos.
- Comparar eficiencia entre métodos.
- Aprender estructuras como HashSet y aplicar encapsulamiento.
