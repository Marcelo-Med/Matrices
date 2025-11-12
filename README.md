# Álgebra Lineal – Operaciones con Matrices  
**Fecha:** 11 de noviembre de 2025  

---

##  Objetivo de la Documentación
El objetivo de este documento es registrar y explicar las **soluciones de los ejercicios de matrices** trabajados en clase, utilizando formato Markdown.  
Se incluyen las operaciones básicas, clasificación de matrices y verificación de propiedades como la **asociatividad del producto matricial**.

---

##  Ejercicio 1: Clasificación de Matrices

###  Enunciado
Identificar el tipo de las siguientes matrices:

\[
A = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}, \quad
B = \begin{pmatrix} 3 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 5 \end{pmatrix}, \quad
C = \begin{pmatrix} 2 & 1 & 4 \\ 1 & 3 & 5 \\ 4 & 5 & 6 \end{pmatrix}, \quad
D = \begin{pmatrix} 1 & 2 & 3 \\ 0 & 4 & 5 \\ 0 & 0 & 6 \end{pmatrix}
\]

###  Solución
- **A:** Matriz identidad  
- **B:** Matriz diagonal  
- **C:** Matriz simétrica  
- **D:** Matriz triangular superior  

###  Proceso
1. Una **matriz identidad** tiene unos en la diagonal principal y ceros en el resto.  
2. Una **matriz diagonal** sólo tiene elementos distintos de cero en la diagonal.  
3. Una **matriz simétrica** cumple que \(C = C^T\).  
4. Una **matriz triangular superior** tiene ceros por debajo de la diagonal.

---

##  Ejercicio 2: Operaciones con Matrices

###  Enunciado
Dadas las matrices:
\[
A = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}, \quad
B = \begin{pmatrix} 6 & 9 \\ 2 & 6 \end{pmatrix}
\]

Realizar las siguientes operaciones:

---

### a) \(A + B\)
\[
A + B = \begin{pmatrix} 7 & 9 \\ 2 & 7 \end{pmatrix}
\]

**Proceso:**
- Sumar cada elemento correspondiente:  
  \( (1+6), (0+9), (0+2), (1+6) \)

---

### b) \(2A - B\)
\[
2A - B = \begin{pmatrix} -1 & -9 \\ -2 & -4 \end{pmatrix}
\]

**Proceso:**
1. Multiplicar \(A\) por 2 → \(\begin{pmatrix} 2 & 0 \\ 0 & 2 \end{pmatrix}\)
2. Restar \(B\): \(2A - B = \begin{pmatrix} 2-3 & 0-0 \\ 0-0 & 2-5 \end{pmatrix}\)

*(Nota: el resultado mostrado en libreta puede tener una ligera variación dependiendo de la matriz original B usada.)*

---

### c) \(A \times B\)
\[
AB = \begin{pmatrix} 11 & 11 \\ 11 & 18 \end{pmatrix}
\]

**Proceso:**
1. Multiplicar filas de A por columnas de B.  
2. Aplicar la fórmula general:  
   \((AB)_{ij} = \sum_k a_{ik}b_{kj}\)

---

### d) \(B \times A\)
\[
BA = \begin{pmatrix} 10 & 8 \\ 7 & 13 \end{pmatrix}
\]

**Proceso:**
- Multiplicación de B por A en orden inverso.  
- El resultado puede diferir de \(AB\), mostrando que **la multiplicación de matrices no es conmutativa**.

---

### e) \(A^T\)
\[
A^T = \begin{pmatrix} 2 & 4 \\ -1 & 4 \end{pmatrix}
\]

**Proceso:**
- Se intercambian filas por columnas.

---

##  Ejercicio 3: Propiedad Asociativa del Producto Matricial

###  Enunciado
Verificar que:
\[
(AB)C = A(BC)
\]

Con las matrices:

\[
A = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}, \quad
B = \begin{pmatrix} 2 & 9 \\ 1 & 3 \end{pmatrix}, \quad
C = \begin{pmatrix} 1 & 1 \\ 0 & 2 \end{pmatrix}
\]

---

###  Solución
\[
(AB)C = A(BC) = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
\]

---

###  Procedimiento paso a paso

1. **Calcular AB**
   \[
   AB = \begin{pmatrix} 4 & 6 \\ 10 & 12 \end{pmatrix}
   \]

2. **Multiplicar (AB)C**
   \[
   (AB)C = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
   \]

3. **Calcular BC**
   \[
   BC = \begin{pmatrix} 2 & 2 \\ 1 & 7 \end{pmatrix}
   \]

4. **Multiplicar A(BC)**
   \[
   A(BC) = \begin{pmatrix} 4 & 16 \\ 10 & 34 \end{pmatrix}
   \]

5. **Conclusión:**  
   Dado que \((AB)C = A(BC)\), se **verifica la propiedad asociativa** del producto matricial.

---

##  Conclusión General
Este ejercicio permitió:
- Identificar distintos tipos de matrices.  
- Practicar operaciones básicas: suma, resta, multiplicación y transposición.  
- Comprobar la **no conmutatividad** y **asociatividad** del producto de matrices.  
- Aplicar una **documentación técnica estructurada en Markdown**, útil para repositorios y proyectos de ingeniería.

---

> _Archivo elaborado por: **Marcelo Medina Canto**_  
> _Materia: Álgebra Lineal – Tecnologico de Software_
