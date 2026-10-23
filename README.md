# Aprende typescript en castellano 🇪🇸

![GitHub License](https://img.shields.io/github/license/d3v3l0p3z/aprende-typescript)

![perrete cuqui con una gorra de typescript declarando su amor por el](./assets/readme.jpg)

- [Aprende typescript en español 🇪🇸](advanced/advanced.md#aprende-typescript-en-espaol)
  - [Typescript avanzado](advanced/advanced.md#typescript-avanzado)
    - [Tipos de utilidad](advanced/advanced.md#utility-types)
    - [Tipos mapeados](advanced/advanced.md#mapped-types)
  - Principios solid
    - [[S] Responsabilidad única (Single Responsibility)](solid/s-single-responsibility.md)
    - [[O] Abierto/Cerrado (Open/Closed))](solid/o-open-closed.md)
    - [[L] Sustitución de Liskov (Liskov Substitution)](solid/l-liskov-substitution.md)
    - [[I] Segregación de Interfaces (Interface Segregation)](solid/i-interface-segregation.md)
    - [[D] Inversión de Dependencias (Dependency Inversion)](solid/d-dependency-inversion.md)
  - Patrones de diseño
    - Comportamiento
      - [Iterador (Iterator)](patterns/behavioral/iterator.md)
      - [Mediador (Mediator)](patterns/behavioral/mediator.md)
      - [Observador (Observer)](patterns/behavioral/observer.md)
      - [Publicador-suscriptor (Publisher-Subscriber)](patterns/behavioral/publisher-subscriber.md)
      - [Estrategia (Strategy)](patterns/behavioral/strategy.md)
    - Estructurales
      - [Compuesto (Composite)](patterns/structural/composite.md)
      - [Decorador (Decorator)](patterns/structural/decorator.md)
      - [Fachada (Facade)](patterns/structural/facade.md)
      - [Peso ligero (Flyweight)](patterns/structural/flyweight.md)
      - [Proxy (Proxy)](patterns/structural/proxy.md)
    - Creacionales
      - [Constructor (Constructor)](patterns/creational/builder.md)
      - [Fábrica (Factory)](patterns/creational/factory.md)
      - [Prototipo (Prototype)](patterns/creational/prototype.md)
      - [Instancia única (Singleton)](patterns/creational/singleton.md)
  - Ejercicios
    - Algorithms
      - Linked List
        - [Valores de lista enlazada](exercises/algorithms/linked-list/linked-list-values.md).
        - [Suma de lista](exercises/algorithms/linked-list/sum-list.md).
        - [Obtener valor de nodo](exercises/algorithms/linked-list/get-node-value.md).
        - [Encontrar objetivo](exercises/algorithms/linked-list/find-target.md).
        - [Invertir lista](exercises/algorithms/linked-list/reverse-list.md).
        - [Lista de cremallera](exercises/algorithms/linked-list/zipper-lists.md).
      - Binary tree
        - [Valores de búsqueda en anchura](exercises/algorithms/binary-tree/breadth-first-values.md).
        - [Valores de búsqueda en profundidad](exercises/algorithms/binary-tree/depth-first-values.md).
        - [El árbol incluye](exercises/algorithms/binary-tree/tree-includes.md).
        - [Valor mínimo del árbol](exercises/algorithms/binary-tree/tree-min-value.md).
        - [Suma de árbol](exercises/algorithms/binary-tree/tree-sum.md).
        - [Suma máxima de la ruta del árbol](exercises/algorithms/binary-tree/tree-max-path-sum.md).
        - [Suma máxima de la ruta de la raíz a la hoja](exercises/algorithms/binary-tree/max-root-to-leaf-path-sum.md).
      - Graph
        - [Valores de búsqueda en anchura](exercises/algorithms/graph/breadth-first-values.md).
        - [Construir gráfico por aristas](exercises/algorithms/graph/build-graph-by-edges.md).
        - [Recuento de componentes conectados](exercises/algorithms/graph/connected-components-count.md).
        - [Tiene ruta](exercises/algorithms/graph/has-path.md).
        - [Valores de búsqueda en profundidad](exercises/algorithms/graph/depth-first-values.md).
        - [Ruta no dirigida](exercises/algorithms/graph/undirected-path.md).
    - [Coderpad](https://coderpad.io)
    - [LeetCode](https://leetcode.com)
      - Algorithms
        - Easy
          - [Añadir forma de matriz de entero](exercises/leet-code/algorithms/easy/add-to-array-form-of-integers.md)
          - [Añadir binario](exercises/leet-code/algorithms/easy/add-binary.md)
          - [Más uno](exercises/leet-code/algorithms/easy/plus-one.md)
          - [De numero romano a numero entero](exercises/leet-code/algorithms/easy/roman-to-integer.md)
        - Medium
          - [Añadir dos números](exercises/leet-code/algorithms/medium/add-two-numbers.md)
          - [Multiplicacion de cadenas de texto](https://leetcode.com/algorithms/medium/multiply-strings/)
          - [Subcadena más larga sin caracteres repetidos](exercises/leet-code/algorithms/medium/longest-substring-without-repeating-characters.md)
    - [HackerRank](https://www.hackerrank.com)
      - Algorithms
        - Easy
          - [Una suma muy grande](exercises/hacker-rank/algorithms/easy/a-very-big-sum.md)
          - [Velas de tarta de cumpleaños](exercises/hacker-rank/algorithms/easy/birthday-cake-candles.md)
          - [Rompiendo los récords](exercises/hacker-rank/algorithms/easy/breaking-records.md)
          - [Comparar los tripletes](exercises/hacker-rank/algorithms/easy/compare-the-triplets.md)
          - [Diferencia diagonal](exercises/hacker-rank/algorithms/easy/diagonal-difference.md)
          - [Suma mínima máxima](exercises/hacker-rank/algorithms/easy/mini-max-sum.md)
          - [Más menos](exercises/hacker-rank/algorithms/easy/plus-minus.md)
          - [Cadena repetida](exercises/hacker-rank/algorithms/easy/repeated-string.md)
          - [Suma de matriz simple](exercises/hacker-rank/algorithms/easy/simple-array-sum.md)
          - [Resuélveme primero](exercises/hacker-rank/algorithms/easy/solve-me-first.md)
          - [Escalera](exercises/hacker-rank/algorithms/easy/staircase.md)
          - [Conversión de tiempo](exercises/hacker-rank/algorithms/easy/time-conversion.md)
        - Medium
          - [Subiendo en la tabla de clasificación](exercises/hacker-rank/algorithms/medium/climbing-the-leaderboard.md)
    - Real code interviews
      - [Contar duplicados](exercises/real-code-interviews/count-dupes.md)
      - [Crear un diccionario](exercises/real-code-interviews/create-dictionary.md)
      - [Perder el contexto](exercises/real-code-interviews/lose-context.ts)
      - [Manipular fetch](exercises/real-code-interviews/manipulate-fetch.md)

## Instala el entorno

Instala las dependencias para ejecutar todos los comandos:

```bash
npm i
```

## Prueba los ejercicios

Para comprobar el código fuente de los ejercicios, puedes usar el siguiente comando:

```bash
npm tests
```

## Añadir nuevos ejercicios

Puedes añadir un nuevo ejercicio con su prueba siguiendo el mismo patrón:

```text
my-new-exercise-file.ts        // Código fuente del ejercicio
my-new-exercise-file.test.ts   // Código de prueba del ejercicio
```

Para escribir el código fuente mientras se ejecutan las pruebas, puedes ejecutar:

```bash
npm run test:watch
```
