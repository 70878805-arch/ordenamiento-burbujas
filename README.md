# Aplicación ordenamiento con el algoritmo de la burbuja 
---
## Descripción del algoritmo
El algoritmo de la burbuja es una forma sencilla de ordenar una lista (por ejemplo, números) de menor a mayor.
Se llama “burbuja” porque los valores grandes van “subiendo” poco a poco hacia el final de la lista, como burbujas en el agua.

🧠 Idea principal

El algoritmo:

Compara dos elementos vecinos en la lista

Si están en el orden incorrecto, los intercambia

Recorre la lista muchas veces

Repite hasta que todo esté ordenado

En cada pasada completa, el elemento más grande “viaja” al final.

---
🔁 Explicación paso a paso

Imagina esta lista:

[5, 2, 4, 1]


👉 Comparo 5 y 2 → están mal → los cambio

👉 Comparo 5 y 4 → están mal → los cambio

👉 Comparo 5 y 1 → están mal → los cambio

Ahora queda:

[2, 4, 1, 5]


✔️ El número 5 ya quedó al final (como una burbuja que sube)

Luego vuelvo a empezar, pero ya no miro el último, porque ya está ordenado.

Se repite este proceso hasta que no haya más intercambios.

---

🧩 ¿Qué hace internamente?

> * Usa dos bucles (uno dentro de otro)

> * Compara posiciones i y i + 1

> * Intercambia valores cuando corresponde

---
🐢 Importante sobre el rendimiento

Bubble sort es:

> * fácil de entender 👍

> * fácil de programar 👍

> * pero lento para listas muy grandes 👎

Su complejidad es:

> * ⏱️ O(n²) — dos ciclos anidados

 * Para estudiar es perfecto; para producción, no tanto.

