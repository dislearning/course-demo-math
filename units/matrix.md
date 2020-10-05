# Matrizes

Una matriz es un objeto matemático de la forma:

$$
  A_{m\times n} = \begin{pmatrix}
    a_{11} & a_{12} & \cdots & a_{1n} \\
    a_{21} & a_{22} & \cdots & a_{2n} \\
    \vdots  & \vdots  & \ddots & \vdots  \\
    a_{m1} & a_{m2} & \cdots & a_{mn} 
  \end{pmatrix}
$$

## Matrices singulares

Existen diferentes tipos de matrices singulares:

- **Matriz fila:** $\mathfrak{M}_{1n}(\mathbb{K})$
  $$
    A_{1n} = \begin{pmatrix}
      a_{11} & a_{12} & \cdots & a_{1n} \\
    \end{pmatrix}
  $$

- **Matriz columna:** $\mathfrak{M}_{m1}(\mathbb{K})$
  $$
    A_{m1} = \begin{pmatrix}
      a_{11} \\
      a_{21} \\
      \vdots \\
      a_{m1} 
    \end{pmatrix}
  $$

- **Matriz cuadrada:** $\mathfrak{M}_{n}(\mathbb{K})$
  $$
    A_{n} = \begin{pmatrix}
      a_{11} & a_{12} & \cdots & a_{1n} \\
      a_{21} & a_{22} & \cdots & a_{2n} \\
      \vdots  & \vdots  & \ddots & \vdots  \\
      a_{n1} & a_{n2} & \cdots & a_{nn} 
    \end{pmatrix}
  $$

- **Matriz Identidad:** Cuyos elementos de la diagonal principal son $1$ y el resto son $0$
  $$
    A_{n} = \begin{pmatrix}
      1 & 0 & \cdots & 0 \\
      0 & 1 & \cdots & 0 \\
      \vdots  & \vdots  & \ddots & \vdots  \\
      0 & 0 & \cdots & 1 
    \end{pmatrix}
  $$
