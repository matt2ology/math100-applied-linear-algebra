# Study Guide for Exam 1 (Sections 1.1 - 1.7)

- [Study Guide for Exam 1 (Sections 1.1 - 1.7)](#study-guide-for-exam-1-sections-11---17)
  - [1. Be able to use the row reduction process to transform a matrix to RREF and REF](#1-be-able-to-use-the-row-reduction-process-to-transform-a-matrix-to-rref-and-ref)
    - [1.1 Row Echelon Form (REF) and Reduced Row Echelon Form (RREF)](#11-row-echelon-form-ref-and-reduced-row-echelon-form-rref)
      - [Practice 1.1.1](#practice-111)
      - [Practice 1.1.1 Solution](#practice-111-solution)
      - [Practice 1.1.2](#practice-112)
      - [Practice 1.1.2 Solution](#practice-112-solution)
      - [Practice 1.1.3](#practice-113)
      - [Practice 1.1.3 Solution](#practice-113-solution)
      - [Practice 1.1.4](#practice-114)
      - [Practice 1.1.4 Solution](#practice-114-solution)
      - [Practice 1.1.5](#practice-115)
      - [Practice 1.1.5 Solution](#practice-115-solution)
      - [Practice 1.1.6](#practice-116)
      - [Practice 1.1.6 Solution](#practice-116-solution)
  - [2. Be able to solve linear systems](#2-be-able-to-solve-linear-systems)
    - [2.1 Augmented Matrixes and Solution Sets](#21-augmented-matrixes-and-solution-sets)
    - [2.2. Determine if Systems are Consistent/Inconsistent and Number of Solutions](#22-determine-if-systems-are-consistentinconsistent-and-number-of-solutions)
    - [2.3 Wriet Solution Sets in Parametric Form](#23-wriet-solution-sets-in-parametric-form)
    - [2.4 Interpret Solution Sets Geometrically (point, line, or plane)](#24-interpret-solution-sets-geometrically-point-line-or-plane)
  - [3. Multiply a Matrix by a Vector](#3-multiply-a-matrix-by-a-vector)
  - [4. Solve Vector and Matrix Equations](#4-solve-vector-and-matrix-equations)
    - [4.1. Usual process: convert to an augmented matrix and then solve as a linear system](#41-usual-process-convert-to-an-augmented-matrix-and-then-solve-as-a-linear-system)
  - [5. Determine if Vectors are Linear Combinations of other Vectors in Span](#5-determine-if-vectors-are-linear-combinations-of-other-vectors-in-span)
    - [5.1. Determining Consistency via Augmented Matrix and Solving Linear Systems](#51-determining-consistency-via-augmented-matrix-and-solving-linear-systems)
    - [5.2. Make sure you understand the definitions of "linear combination" and "span"](#52-make-sure-you-understand-the-definitions-of-linear-combination-and-span)
  - [6. Determining Linear Combinations and Determining Span](#6-determining-linear-combinations-and-determining-span)
    - [6.1. Determining Linear Combinations](#61-determining-linear-combinations)
  - [7. Be able to determine if $v\_1,:v\_2,:\\dots ,:v\_k$ are linearly independent or linearly dependent](#7-be-able-to-determine-if-v_1v_2dots-v_k-are-linearly-independent-or-linearly-dependent)
  - [8. Be able to solve network flow problems](#8-be-able-to-solve-network-flow-problems)

## 1. Be able to use the row reduction process to transform a matrix to RREF and REF

### 1.1 Row Echelon Form (REF) and Reduced Row Echelon Form (RREF)

Make sure you can recognize when a matrix is in Row Echelon Form (REF) and Reduced Row Echelon Form (RREF)

> Definition: Row Echelon (staircase) Forms
>
> A matrix A is in **row echelon form (REF)** if
>
> 1. all nonzero rows lie above any rows of all zeros;
> 2. the leading entry (from the left) of each nonzero row is strictly to the right of the leading entry of the row above it.
>
> A matrix A is in **reduced row echelon form (RREF)** if,
> in addition to **1.** and **2.**, it also satisfies
>
> 3. the leading entry (from the left) of each nonzero row is a `1` (called the **leading one**);
> 4. each leading one is the only nonzero entry in its column.

Determine if each of the following are in REF or RREF.
If in REF re-write as RREF.

#### Practice 1.1.1

$\begin{bmatrix} 1&2&3&0\\ 0&1&3&1\\ 0&0&0&1 \end{bmatrix}$

- [x] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

#### Practice 1.1.1 Solution

> Reason
>
> > To determine if the matrix is in **row echelon from (REF)**
> >
> > 1. ✅ All non-zeros lie above any rows of all zeros
> > 2. ✅ The **leading entry** (from the left) of each non-zero row is strictly to the right of the leading entry of the row above it
> >
> > Now to determine if the matrix is in **reduced row echelon form (RREF)**
> >
> > 3. ✅ The leading entry (from the left) of each non-zero row is a `1` (called the **leading one**);
> > 4. ❌ No **leading one** present in $x_3$: leading one is the only non-zero entry in its column.

#### Practice 1.1.2

$\begin{bmatrix}1&2&3\\ 0&2&5\\ 0&6&7\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [x] Neither

#### Practice 1.1.2 Solution

> Reason
>
> > To determine if the matrix is in **row echelon from (REF)**
> >
> > 1. ✅ All non-zeros lie above any rows of all zeros
> > 2. ❌ $r_{23}$ ($x_2$ row 3) violates: The **leading entry** (from the left) of each non-zero row is strictly to the right of the leading entry of the row above it

#### Practice 1.1.3

$\begin{bmatrix}1&0&1&0&7\\ 0&0&0&1&3\\ 0&0&0&0&0\end{bmatrix}$

- [ ] The matrix is in REF
- [x] The matrix is in RREF
- [ ] Neither

#### Practice 1.1.3 Solution

> Reason
>
> > To determine if the matrix is in **row echelon from (REF)**
> >
> > 1. ✅ All non-zeros lie above any rows of all zeros
> > 2. ✅ The **leading entry** (from the left) of each non-zero row is strictly to the right of the leading entry of the row above it
> >
> > Now to determine if the matrix is in **reduced row echelon form (RREF)**
> >
> > 3. ✅ The leading entry (from the left) of each non-zero row is a `1` (called the **leading one**);
> > 4. ✅ leading one is the only non-zero entry in its column.

#### Practice 1.1.4

$\begin{bmatrix}0&0&0&0\\ 0&1&0&1\\ 0&0&0&1\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [x] Neither

#### Practice 1.1.4 Solution

> Reason
>
> > To determine if the matrix is in **row echelon from (REF)**
> >
> > 1. ❌ All non-zeros lie above any rows of all zeros

#### Practice 1.1.5

\(e\) $\begin{bmatrix}0&0&0\\ 0&7&6\\ 2&3&4\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [x] Neither

#### Practice 1.1.5 Solution

> Reason
>
> > To determine if the matrix is in **row echelon from (REF)**
> >
> > 1. ✅ All non-zeros lie above any rows of all zeros
> > 2. ❌ $r_{31}$ ($r_{column-row}$): The **leading entry** (from the left) of each non-zero row is strictly to the right of the leading entry of the row above it

#### Practice 1.1.6

\(f\) $\begin{bmatrix} 3&0&1&6\\ 0&2&4&3\\ 0&0&1&3\end{bmatrix}$

- [x] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

#### Practice 1.1.6 Solution

> Reason
>
> > To determine if the matrix is in **row echelon from (REF)**
> >
> > 1. ✅ All non-zeros lie above any rows of all zeros
> > 2. ✅ The **leading entry** (from the left) of each non-zero row is strictly to the right of the leading entry of the row above it
> >
> > Now to determine if the matrix is in **reduced row echelon form (RREF)**
> >
> > 3. ❌ The leading entry (from the left) of each non-zero row is a `1` (called the **leading one**);
> > 4. ❌ No **leading one** present in $x_3$: leading one is the only non-zero entry in its column.

## 2. Be able to solve linear systems

### 2.1 Augmented Matrixes and Solution Sets

_Usual process_:

1. Write as augmented matrix
2. Row reduce to REF or RREF
3. Write the solution set (using free variables if necessary)

### 2.2. Determine if Systems are Consistent/Inconsistent and Number of Solutions

Be able to determine if the system is consistent/inconsistent and if there are
infinitely many solutions

### 2.3 Wriet Solution Sets in Parametric Form

Be able to write the solution set in parametric vector form

### 2.4 Interpret Solution Sets Geometrically (point, line, or plane)

Be able to interpret solution sets geometrically: point, line, or plane

## 3. Multiply a Matrix by a Vector

Be able to multiply a matrix by a vector

## 4. Solve Vector and Matrix Equations

Be able to solve vector and matrix equations of the form
$x_1\overline{v}_1\:+\:x_2\overline{v}_2\:+\:·\:·\:·\:+\:x_n\overline{v}_n\:=\:b\:and\:A\overline{x}\:=\:b$

### 4.1. Usual process: convert to an augmented matrix and then solve as a linear system

## 5. Determine if Vectors are Linear Combinations of other Vectors in Span

Be able to determine if a vector `b` is a linear combination of the vectors $v_1,\:v_2,\:\dots ,v_k$; this is the same as determining if `b` is in Span $\left\{v_1,\:v_2,\:\dots ,\:v_k\right\}$

### 5.1. Determining Consistency via Augmented Matrix and Solving Linear Systems

**Usual process**:
determine if $x_1\overline{v}_1\:+\:x_2\overline{v}_2\:+\:\dots \:+x_k\overline{v}
_k\:=\:b$ is consistent by converting to an augmented matrix and solving as a linear system

### 5.2. Make sure you understand the definitions of "linear combination" and "span"

## 6. Determining Linear Combinations and Determining Span

Be able to determine if _every_ $b\:\in \mathbb{R}^m$ is a linear combination of $v_1,\:v_2,\:\dots ,\:v_k$; this is the same as determining if every _every_ $b\:\in \mathbb{R}^m$ is in Span$\left\{v_1,\:v_2,\:\dots \:,\:v_k\right\}$

### 6.1. Determining Linear Combinations

Usual process:

1. Make the "coefficient" matrix $\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\right]$
2. Row reduce to REF
3. If there is a pivot in every `row`, then YES, $b\:\in \mathbb{R}^m$ is a linear combination $v_1,\:v_2,\:\dots ,\:v_k$; if there is NOT a pivot in every `row`, then NO

- Note: for this type of problem, you only need to work with the
  $\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\right]$ instead of the full
  augmented matrix $\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\:|\:b\:\right]$

## 7. Be able to determine if $v_1,\:v_2,\:\dots ,\:v_k$ are linearly independent or linearly dependent

## 8. Be able to solve network flow problems

The main principle is that "flow in = flow out" at every intersection.
Also, the flow into the entire network must equal the flow out of the entire
network.
