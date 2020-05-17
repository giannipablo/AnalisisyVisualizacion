# Ejercicio 1 
## Medidas de probabilidad

El experimento consiste en lanzar una moneda tres veces y observar la sucesión de caras y cecas.

#### 1. $\Omega = \{a_1, \dots, a_k\}$ y luego $k = \#\Omega$

La moneda tiene dos lados equiprobables, el resultado de cada volado es independiente del anterior, al menos eso asumo. Por lo tanto, tengo $k = 2^3 = 8$ combinaciones de resultados posibles. $\Omega$ es

T|t1|t2|t3
---|---|---|---
1 |c |c |c 
2 |c |c |x
3 |c |x |c
4 |c |x |x
5 |x |c |c
6 |x |c |x
7 |x |x |c
8 |x |x |x

donde $t_i$ con $i \in [1,2,3]$ representa el resultado de la tirada $i$-esima

#### 2. $\textbf{P}(A)$, probabilidad de que salgan dos o más caras, e identificar $A$

El evento $A = \{T_1, T_2, T_3, T_5\}$ y 

\begin{eqnarray} 
\textbf{P}(A)&=& \frac{\#A}{\#\Omega} = \frac{4}{8} \\
&=& \frac{1}{2}
\end{eqnarray}

#### 3. Probabilidad que salgan menos de dos caras

La probabilidad de que salgan menos de dos caras se puede pensar como el complemento de $A$, o sea $A^c = \{T_4, T_6, T_7, T_8\}$ donde

\begin{eqnarray}   
\textbf{P}(A^c)&=& 1 - \textbf{P}(A)\\
&=& 1 - {1\over 2}\\
&=& {1 \over 2}
\end{eqnarray}