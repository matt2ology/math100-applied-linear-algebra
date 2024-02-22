# Study Guide for Exam 1 (Sections 1.1 - 1.7)

- [Study Guide for Exam 1 (Sections 1.1 - 1.7)](#study-guide-for-exam-1-sections-11---17)
  - [1. Be able to use the row reduction process to transform a matrix to RREF and REF](#1-be-able-to-use-the-row-reduction-process-to-transform-a-matrix-to-rref-and-ref)
    - [Practice 1.1.1](#practice-111)
    - [Practice 1.1.2](#practice-112)
    - [Practice 1.1.3](#practice-113)
    - [Practice 1.1.4](#practice-114)
    - [Practice 1.1.5](#practice-115)
    - [Practice 1.1.6](#practice-116)
  - [2. Be able to solve linear systems](#2-be-able-to-solve-linear-systems)
    - [2.1. Augmented Matrixes and Solution Sets](#21-augmented-matrixes-and-solution-sets)
      - [Practice 2.1.1](#practice-211)
      - [Practice 2.1.2](#practice-212)
      - [Practice 2.1.3](#practice-213)
      - [Practice 2.1.4](#practice-214)
      - [Practice 2.1.5](#practice-215)
      - [Practice 2.1.6](#practice-216)
      - [Practice 2.1.7](#practice-217)
      - [Practice 2.1.8](#practice-218)
    - [2.2. Consistant/Inconsistent Systems and Number of Solutions](#22-consistantinconsistent-systems-and-number-of-solutions)
    - [2.3. Solution Sets in Parametric Vector Form](#23-solution-sets-in-parametric-vector-form)
    - [2.4. Interpret Solution Sets Geometrically (Point, line, or plane)](#24-interpret-solution-sets-geometrically-point-line-or-plane)
  - [3. Multiply a matrix by a vector](#3-multiply-a-matrix-by-a-vector)
  - [4. SOlve Vector and Matrix Equations of the Form](#4-solve-vector-and-matrix-equations-of-the-form)
    - [4.1. Convert to an augmented matrix and then solve as a linear system](#41-convert-to-an-augmented-matrix-and-then-solve-as-a-linear-system)
  - [5. Determine if a vector b is a linear combination of the vectors](#5-determine-if-a-vector-b-is-a-linear-combination-of-the-vectors)
    - [5.1. Converting an Augmented Matrix and Solving as a Linear ystem](#51-converting-an-augmented-matrix-and-solving-as-a-linear-ystem)
    - [5.2. Definitions of "Linear Combination" and "Span"](#52-definitions-of-linear-combination-and-span)
  - [6. Differences Between "Linear Combination" and "Span"](#6-differences-between-linear-combination-and-span)
    - [6.1. Determine Linear Combinations in $\\left\[v\_1::::v\_2::::\\dots ::::v\_k\\right\]$](#61-determine-linear-combinations-in-leftv_1v_2dots-v_kright)
  - [7. Be able to determine if $v\_1,:v\_2,:\\dots ,:v\_k$ are linearly independent or linearly dependent](#7-be-able-to-determine-if-v_1v_2dots-v_k-are-linearly-independent-or-linearly-dependent)
    - [7.1. Linearly Independency, Number of Solutions, and Free variables](#71-linearly-independency-number-of-solutions-and-free-variables)
    - [7.2. Solving Systems and Number of Solutions](#72-solving-systems-and-number-of-solutions)
    - [7.3. Theorems and Ideas](#73-theorems-and-ideas)
  - [8. Application - Solve Network Flow Problems](#8-application---solve-network-flow-problems)
    - [8.1. Network Flows](#81-network-flows)


## 1. Be able to use the row reduction process to transform a matrix to RREF and REF

**1.1** Make sure you can recognize when a matrix is in Row Echelon Form (REF) and Reduced Row Echelon Form (RREF)

Determine if each of the following are in REF or RREF.

### Practice 1.1.1

$\begin{bmatrix} 1&2&3&0\\ 0&1&3&1\\ 0&0&0&1 \end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

### Practice 1.1.2

$\begin{bmatrix}1&2&3\\ 0&2&5\\ 0&6&7\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

### Practice 1.1.3

$\begin{bmatrix}1&0&1&0&7\\ 0&0&0&1&3\\ 0&0&0&0&0\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

### Practice 1.1.4

$\begin{bmatrix}0&0&0&0\\ 0&1&0&1\\ 0&0&0&1\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

### Practice 1.1.5

$\begin{bmatrix}0&0&0\\ 0&7&6\\ 2&3&4\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

### Practice 1.1.6

$\begin{bmatrix} 3&0&1&6\\ 0&2&4&3\\ 0&0&1&3\end{bmatrix}$

- [ ] The matrix is in REF
- [ ] The matrix is in RREF
- [ ] Neither

## 2. Be able to solve linear systems

### 2.1. Augmented Matrixes and Solution Sets

_Usual process_:

1. Write as augmented matrix
2. Row reduce to REF or RREF
3. Write the solution set (using free variables if necessary)

#### Practice 2.1.1

$\begin{cases} 20x&&+87z&=&-33\\ 1x&-7y&-87z&=&-8\\ 60x&+90y&&=&5 \end{cases}$

$\left[\begin{array}{ccc|c} \_\_\_&\_\_\_&\_\_\_&\_\_\_\\ \_\_\_&\_\_\_&\_\_\_&\_\_\_\\ \_\_\_&\_\_\_&\_\_\_&\_\_\_ \end{array}\right]$

#### Practice 2.1.2

$\begin{cases} 5x_1+3x_2-4x_3=-13\\ 2x_1-2x_2+5x_3=-28 \end{cases}$

#### Practice 2.1.3

$\begin{cases} -4x&+&2y&+&5z&=&-29&\\ 5x&-&2y&+&2z&=&-5&\\ -5x&-&5y&+&6z&=&-35& \end{cases}$

#### Practice 2.1.4

$\begin{cases} 2x&-&5y&+&3z&=&-13\\ x&+&2y&-&4z&=&19\\ -4x&-&3y&-&4z&=&-6 \end{cases}$

#### Practice 2.1.5

$\begin{cases} -10x&+&10y&-&6z&=&10\\ 20x&-&20y&+&12z&=&-20\\ -30x&+&30y&-&18z&=&30 \end{cases}$

- [ ] No Solution
- [ ] Infinite Number of Solutions
- [ ] Unique Solution

#### Practice 2.1.6

$\begin{cases}&-4x&-&16y&-&61z&=&6\\ &4x&+&17y&+&63z&=&10\\ &x&+&4y&+&15z&=&0 \end{cases}$

- [ ] No Solution
- [ ] Infinite Number of Solutions
- [ ] Unique Solution

#### Practice 2.1.7

$\begin{cases}&3x&+&3y&-&3z&=&-5\\ &-3x&+&5y&+&5z&=&-3\\ &9x&+&25y&-&5z&=&-28 \end{cases}$

- [ ] No Solution
- [ ] Infinite Number of Solutions
- [ ] Unique Solution

#### Practice 2.1.8

$\begin{cases}&3x&+&3y&-3z&=&-5\\ &-3x&+&5y&+5z&=&-3\\ &9x&+&25y&-5z&=&-31\end{cases}$

- [ ] No Solution
- [ ] Infinite Number of Solutions
- [ ] Unique Solution

### 2.2. Consistant/Inconsistent Systems and Number of Solutions

Be able to determine if the system is consistent/inconsistent and if there are infinitely many solutions

### 2.3. Solution Sets in Parametric Vector Form

Be able to write the solution set in parametric vector form

### 2.4. Interpret Solution Sets Geometrically (Point, line, or plane)

Be able to interpret solution sets geometrically: point, line, or plane

## 3. Multiply a matrix by a vector

Be able to multiply a matrix by a vector

## 4. SOlve Vector and Matrix Equations of the Form

Be able to solve vector and matrix equations of the form $x_1\overline{v}_1\:+\:x_2\overline{v}_2\:+\:·\:·\:·\:+\:x_n\overline{v}_n\:=\:b\:and\:A\overline{x}\:=\:b$

### 4.1. Convert to an augmented matrix and then solve as a linear system

Usual process: convert to an augmented matrix and then solve as a linear system

## 5. Determine if a vector b is a linear combination of the vectors

Be able to determine if a vector b is a linear combination of the vectors
$v_1,\:v_2,\:\dots ,v_k$; this is the same as determining if $b$ is in
Span $\left\{v_1,\:v_2,\:\dots ,\:v_k\right\}$

### 5.1. Converting an Augmented Matrix and Solving as a Linear ystem

**Usual process**: determine if
$x_1\overline{v}_1\:+\:x_2\overline{v}_2\:+\:\dots \:+x_k\overline{v}_k\:=\:b$
is consistent by converting to an augmented matrix and solving as a linear
system

### 5.2. Definitions of "Linear Combination" and "Span"

Make sure you understand the definitions of "linear combination" and "span"

## 6. Differences Between "Linear Combination" and "Span"

Be able to determine if _every_ $b\:\in \mathbb{R}^m$ is a linear combination of $v_1,\:v_2,\:\dots ,\:v_k$; this is the same as determining if every _every_ $b\:\in \mathbb{R}^m$ is in Span$\left\{v_1,\:v_2,\:\dots \:,\:v_k\right\}$

### 6.1. Determine Linear Combinations in $\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\right]$

**Usual process**:

1. Make the "coefficient" matrix $\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\right]$
2. Row reduce to REF
3. If there is a pivot in every `row`, then YES, $b\:\in \mathbb{R}^m$ is a linear combination $v_1,\:v_2,\:\dots ,\:v_k$; if there is NOT a pivot in every `row`, then NO

**6.2.** Note: for this type of problem, you only need to work with the
  $\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\right]$ instead of the full
  augmented matrix $\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\:|\:b\:\right]$

## 7. Be able to determine if $v_1,\:v_2,\:\dots ,\:v_k$ are linearly independent or linearly dependent

### 7.1. Linearly Independency, Number of Solutions, and Free variables

The definition: $v_1,\:v_2,\:\dots ,\:v_k$ are linearly independent
if and only if $x_1\overline{v}_1+x_2\overline{v}_2+\dots +x_k\overline{v}_k=0$
has only one solution (i.e. if there are no free variables)

### 7.2. Solving Systems and Number of Solutions

**Usual process**: solve the system
$\left[v_1\:\:\:\:v_2\:\:\:\:\dots \:\:\:\:v_k\:|\:0\:\right]$ and determine
how many solutions there are

### 7.3. Theorems and Ideas

There are also some theorems that can sometimes help:

- Assume $v_1,\:v_2,\:\dots ,\:v_k$ are in $\mathbb{R}^m$. If $k>m$, then the vectors must be linearly dependent.

- If one of $v_1,\:v_2,\:\dots ,\:v_k$ is the zero vector, then the vectors must be linearly dependent.

- Two vectors $v_1,\:v_2$ are linearly dependent if and only if one is a scalar multiple of the other

## 8. Application - Solve Network Flow Problems

Be able to solve network flow problems

### 8.1. Network Flows

The main principle is that "flow in = flow out" at every intersection.
Also, the flow into the entire network must equal the flow out of the entire
network.
