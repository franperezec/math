# Clase 1: Elementos de lógica y conjuntos

## Descripción
En esta clase, abordaremos los elementos fundamentales de lógica y conjuntos. Los estudiantes aprenderán los conceptos básicos que son esenciales para la matemática y la programación.

### Introducción a la lógica proposicional y conjuntos numéricos

#### I. Lógica Proposicional

##### A. Conectores lógicos básicos

1. Conjunción (∧): "y"
2. Disyunción (∨): "o"
3. Negación (¬): "no"
4. Implicación (→): "si... entonces"
5. Doble implicación (↔): "si y solo si"

##### B. Tablas de verdad

Ejemplo de tabla de verdad para P → Q:

| P | Q | P → Q |
|---|---|-------|
| V | V |   V   |
| V | F |   F   |
| F | V |   V   |
| F | F |   V   |

Nota: La implicación solo es falsa cuando el antecedente es verdadero y el consecuente es falso.

##### C. Cuantificadores lógicos

1. Existencial (∃): "Existe"
2. Universal (∀): "Para todo"

Ejemplos:
- ∃x ∀y: "Existe un x para todo y"
- ∀y ∃x: "Para todo y existe un x"

Importante: El orden de los cuantificadores afecta el significado lógico.

Analogía: "Todos tienen una madre, ninguna como la mía"
- ∃x ∀y: Existe una madre para todas las personas (incorrecto)
- ∀y ∃x: Para toda persona existe una madre (correcto)

##### D. Negación de cuantificadores

- Negación de ∃x P(x): ∀x ¬P(x)
- Negación de ∀x P(x): ∃x ¬P(x)

#### II. Conjuntos Numéricos

##### A. Conjuntos numéricos básicos y notación

1. Números naturales (ℕ): {0, 1, 2, 3, ...}
   - Nota: Existe ambigüedad sobre la inclusión del 0 (varía según el país)
2. Enteros (ℤ): Incluye naturales y negativos
3. Números racionales (ℚ): Forma n/m, donde n ∈ ℤ y m ∈ ℕ
4. Números reales (ℝ): Representados en la recta real

##### B. Relación de contención

ℕ ⊂ ℤ ⊂ ℚ ⊂ ℝ

##### C. Notación matemática

- Doble barra (ejemplo: ℕ): Indica un conjunto bien definido
- ℕ: Naturales
- ℤ: Enteros
- ℚ: Racionales (Q por "cociente")
- ℝ: Reales

## Material de Clase
- <a href="https://colab.research.google.com/drive/1rT5dKe91D9AZrai4kijw_8ZaSJwuZBrP?usp=sharing" target="_blank">Jupyter Notebook de la Clase</a>
- <a href="https://miro.com/app/board/uXjVK5MP8Ms=/?share_link_id=136644180414" target="_blank">Apuntes de Clase</a>
- <a href="https://quizizz.com/join?gc=82817068" target="_blank">Preguntas de Práctica y Fichas de Estudio</a>
- <a href="https://youtu.be/xhAM6WZEtoo" target="_blank">Video de la Clase</a>

## Objetivos de Aprendizaje
- Comprender los conceptos básicos de lógica.
- Familiarizarse con los conjuntos y sus operaciones.

## Actividades
- Realizar ejercicios en el cuaderno de Colab durante la clase.
- Descargar el cuaderno para práctica adicional.

## Recursos Adicionales
- <a href="https://docs.python.org/" target="_blank">Enlace a la documentación de Python</a>
- <a href="https://www.google.com.ec/books/edition/The_Way_of_Analysis/Yix09oVvI1IC?hl=en&gbpv=1&dq=o+Strichartz+Robert+(2000)+The+Way+of+analysis+Jones+and+Bartlett+books+in+mathematics&printsec=frontcover" target="_blank">Libro de referencia: The Way of Analysis - Robert Strichartz</a>