# 📘 Quiz — Gilbert Strang: *Introduction to Linear Algebra* (5th Edition)

**Scope:** Full course coverage  
**Format:** Mixed (multiple-choice, short answer, proofs)  
**Edition:** 5th Edition (MIT Press, 2016)  
**Author:** Gilbert Strang

---

## 🧭 Instructions

- This quiz covers the main topics from the entire book:
  1. Vectors and linear combinations  
  2. Matrices and linear systems  
  3. Subspaces and the Fundamental Theorem of Linear Algebra  
  4. Orthogonality and projections  
  5. Determinants and eigenvalues  
  6. Symmetric matrices and SVD  
  7. Least squares and numerical methods  
  8. Applications (differential equations, graphs, image processing)

- The **answer key** is included at the end.

---

## 🧩 Questions

### 1. Definition
What does it mean for a set of vectors to be *linearly independent*?

---

### 2. Computation
Solve  
$$
A x = b, \quad A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \quad b = \begin{bmatrix} 5 \\ 11 \end{bmatrix}.
$$

---

### 3. Multiple Choice  
Which statement is true for an invertible $n \times n$ matrix?

A) $\det(A) = 0$  
B) Rank$(A) = n$  
C) $A$ has no inverse  
D) Columns are linearly dependent  

---

### 4. Theory  
Explain the concept and use of the $A = LU$ factorization.

---

### 5. Computation  
Find the eigenvalues and eigenvectors of  
$$
A = \begin{bmatrix} 2 & 1 & 0 \\ 1 & 2 & 1 \\ 0 & 1 & 2 \end{bmatrix}.
$$

---

### 6. Concept  
What are the four fundamental subspaces of a matrix, and how are their dimensions related?

---

### 7. Multiple Choice  
Which properties hold for an orthogonal projection matrix $P$?

A) $P^2 = P$  
B) $P^T = -P$  
C) $P$ is symmetric and idempotent  
D) Both A) and C)  

---

### 8. Computation  
Perform the Gram–Schmidt process on the vectors:  
$[1,1,0]$, $[1,0,1]$, $[0,1,1]$.

---

### 9. Proof  
Prove that if $A$ is symmetric, then its eigenvectors corresponding to distinct eigenvalues are orthogonal.

---

### 10. Determinant  
Compute  
$$
\det \begin{bmatrix} 1 & 2 & 3 \\ 0 & 1 & 4 \\ 5 & 6 & 0 \end{bmatrix}.
$$

---

### 11. Eigenvalues (Theory)
If $\det(A - \lambda I) = -\lambda(\lambda-2)^2$, what can you infer about the Jordan form of $A$?

---

### 12. Concept  
What is the Singular Value Decomposition (SVD), and why is it useful in PCA or image compression?

---

### 13. Computation  
Compute the SVD of  
$$
A = \begin{bmatrix} 3 & 0 \\ 0 & 2 \end{bmatrix}.
$$

---

### 14. Least Squares  
Solve using least squares:
$$
A = \begin{bmatrix} 1 & 1 \\ 1 & 2 \\ 1 & 3 \end{bmatrix}, \quad b = \begin{bmatrix} 1 \\ 2 \\ 2 \end{bmatrix}.
$$

---

### 15. Multiple Choice  
Which statements about the Moore–Penrose pseudoinverse $A^+$ are true?

A) If $A$ is square and invertible, $A^+ = A^{-1}$  
B) $A^+$ always exists  
C) $A^+ = A^T$ for all matrices  
D) Both A) and B)  

---

### 16. Application  
How is linear algebra used to solve systems of differential equations of the form $x' = A x$?

---

### 17. Concept  
State the **spectral theorem** for symmetric matrices.

---

### 18. Computation  
Let  
$$
A = \begin{bmatrix} 4 & 1 \\ 1 & 3 \end{bmatrix}.
$$  
Find its eigenvalues and normalized eigenvectors.

---

### 19. Relationship  
State and explain the **Rank–Nullity Theorem**.

---

### 20. Numerical  
What is the role of pivoting in Gaussian elimination, and why is it important for numerical stability?

---

### 21. Multiple Choice  
Which algorithm is efficient for finding the largest eigenvalue of a large matrix?

A) QR algorithm  
B) Power method  
C) LU factorization  
D) Gram–Schmidt  

---

### 22. Computation  
For  
$$
A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix},
$$  
determine its rank and a basis for its column space.

---

### 23. Proof  
Show that if $Q$ is orthogonal ($Q^T Q = I$), then $\|Qx\| = \|x\|$ for any vector $x$.

---

### 24. Application  
Describe how the Laplacian matrix relates to graphs and what its eigenvalues reveal.

---

### 25. Concept  
What is the *condition number* of a matrix and why does it matter?

---

### 26. Computation  
Compute the 2-norm condition number of  
$$
A = \mathrm{diag}(2, 0.1).
$$

---

### 27. Open  
Briefly explain how SVD can be used for image compression.

---

### 28. Multiple Choice  
Which statements are true for orthogonal matrices?

A) $\det(Q) = \pm 1$  
B) Always diagonalizable over $\mathbb{R}$  
C) $Q^{-1} = Q^T$  
D) A) and C)  

---

### 29. Computation  
If $A^2 = I$, what are the possible eigenvalues of $A$?

---

### 30. Proof  
Prove that $(A^{-1})^T = (A^T)^{-1}$ for any invertible matrix $A$.

---

### 31. Numerical  
Why can classical Gram–Schmidt lose orthogonality, and how do Householder reflections fix this?

---

### 32. Creative  
Choose one real-world application (e.g., networks, image processing, cryptography) and explain which linear algebra tools from Strang’s book would be useful.

---

## ✅ Answer Key (Short Solutions)

1. Linearly independent means only the trivial linear combination gives zero.  
2. $x = [1, 2]^T$.  
3. **B**  
4. $A = LU$; $L$ lower-triangular, $U$ upper-triangular. Used for efficient solving.  
5. Tridiagonal symmetric matrix; eigenvalues $\lambda_k = 2 + 2\cos(k\pi/4)$.  
6. Four subspaces: Col$(A)$, Null$(A)$, Col$(A^T)$, Null$(A^T)$; rank + nullity = n.  
7. **D**  
8. Apply Gram–Schmidt step by step.  
9. Symmetric $A$ ⇒ eigenvectors of distinct eigenvalues are orthogonal.  
10. $\det = 1$.  
11. One eigenvalue 0 (1×1 block), one eigenvalue 2 (may have 2×2 Jordan block).  
12. $A = U\Sigma V^T$; used for compression, noise reduction.  
13. $U = I$, $\Sigma = \mathrm{diag}(3,2)$, $V = I$.  
14. $x ≈ [0.214, 0.714]^T$.  
15. **D**  
16. Solution via $x(t) = e^{At} x_0$; diagonalization helps.  
17. Every real symmetric matrix is orthogonally diagonalizable: $A = Q\Lambda Q^T$.  
18. $\lambda = (7 ± \sqrt{5})/2$, normalized eigenvectors follow.  
19. $\text{dim}(V) = \text{rank}(T) + \text{nullity}(T)$.  
20. Pivoting improves numerical stability by avoiding division by small pivots.  
21. **B**  
22. Rank = 2, column space basis = first two columns.  
23. $\|Qx\|^2 = x^T Q^T Q x = \|x\|^2$.  
24. Laplacian $L = D - A$; eigenvalues show graph connectivity.  
25. Condition number $\kappa(A) = \|A\| \|A^{-1}\|$; large $\kappa$ = instability.  
26. $\kappa_2(A) = 2 / 0.1 = 20$.  
27. Keep top $k$ singular values → low-rank approximation.  
28. **D**  
29. Eigenvalues ±1.  
30. From $(AB)^T = B^T A^T$ with $B = A^{-1}$.  
31. Classic GS suffers rounding errors; Householder is numerically stable.  
32. (Student’s answer: choose application and describe relevant methods.)

---

**End of Quiz**  
📚 *Based on Gilbert Strang – Introduction to Linear Algebra (5th Edition, MIT Press, 2016)*