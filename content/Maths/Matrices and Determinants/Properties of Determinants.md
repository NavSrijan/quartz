### Property 1
The value of determinant remains unaltered, if the rows and columns are inter changed, i.e., if A is an n-rowed square matrix, then $|A| = |A^{'}|$

<mark style="background: #FFB8EBA6;">Only if $\Delta$ is positive.</mark> 

Example:
$$
\begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3 \\
\end{vmatrix}
=
\begin{vmatrix}
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3 \\
c_1 & c_{2}& c_3\\
\end{vmatrix}
$$

### Property 2
If any two rows(or columns) of a determinant be interchanged, the value of determinant is changed in sign only.
Let $$D_1=
\begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3 \\
\end{vmatrix}
\quad and\quad D_2=
\begin{vmatrix}
a_2 & b_2 & c_2 \\
a_1 & b_1 & c_1 \\
a_3 & b_{3}& c_3\\
\end{vmatrix}$$
Then, $$\boxed{D_2=-D_1}$$

<mark style="background: #FFB8EBA6;">If 'n' rows are changed, then the resulting determinant</mark> $\boxed{\Delta^{1}=(-1)^{n}\Delta}$

### Property 3
If a determinant has any two rows (or columns) identical or proportional, then its value is zero.
Let $$D = \begin{vmatrix}
a_1 & b_1 & c_1 \\
a_1 & b_1 & c_1 \\
a_3 & b_3 & c_3 \\
\end{vmatrix}=0$$

### Property 4
If all the elements of any row (or column) be multiplied by the same number, then the determinant is multiplied by that number.
If,
$$\begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3 \\
\end{vmatrix}
\text{ and }D^{'}=
\begin{vmatrix}
Ka_1 & Kb_1 & Kc_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3 \\
\end{vmatrix}$$
then <mark style="background: #FFB8EBA6;">$D^{'}=KD$</mark> 

### Property 5
If each element of any row (or column) can be expressed as a sum of two terms, then the determinant can be expressed as the sum of two determinants.

$$\begin{vmatrix}
a+x & b+y & c+z \\
2 & 3 & 1 \\
p & 1 & r \\
\end{vmatrix}
=
\begin{vmatrix}
a & b & c \\
2 & 3 & 1 \\
p & q & r \\
\end{vmatrix}
+
\begin{vmatrix}
x & y & z \\
2 & 3 & 1 \\
p & q & r \\
\end{vmatrix}
$$

#### Proof:
Let 
$$\Delta = \begin{vmatrix}
a_1+\alpha_1 & b_1 & c_1 \\
a_2+\alpha_2 & b_2 & c_2 \\
a_3+\alpha_3 & b_3 & c_3 \\
\end{vmatrix}$$
Expanding $\Delta$ along the first column, we get
$$D=(a_{1}+\alpha_1)\begin{vmatrix}
b_2 & c_1 \\
b_3 & c_3 \\
\end{vmatrix}
-
(a_{2}+\alpha_2)\begin{vmatrix}
b_1 & c_1 \\
b_3 & c_3 \\
\end{vmatrix}
+
(a_{3}+\alpha_3)\begin{vmatrix}
b_1 & c_1 \\
b_2 & c_2 \\
\end{vmatrix}
$$

$$=(a_1\begin{vmatrix}
b_2 & c_1 \\
b_3 & c_3 \\
\end{vmatrix}
-
a_2\begin{vmatrix}
b_1 & c_1 \\
b_3 & c_3 \\
\end{vmatrix}
+
a_3\begin{vmatrix}
b_1 & c_1 \\
b_2 & c_2 \\
\end{vmatrix})

+

(\alpha_1\begin{vmatrix}
b_2 & c_1 \\
b_3 & c_3 \\
\end{vmatrix}
-
\alpha_2\begin{vmatrix}
b_1 & c_1 \\
b_3 & c_3 \\
\end{vmatrix}
+
\alpha_3\begin{vmatrix}
b_1 & c_1 \\
b_2 & c_2 \\
\end{vmatrix})
$$
$$=\begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3 \\
\end{vmatrix}
+
\begin{vmatrix}
\alpha_1 & b_1 & c_1 \\
\alpha_2 & b_2 & c_2 \\
\alpha_3 & b_3 & c_3 \\

\end{vmatrix}$$

We can also conclude that
$$\boxed{\begin{vmatrix}
    a_{1}+mb_1       & b_{1} & c_{1}\\
    a_{2}+mb_2       & b_{2} & c_{2}\\
    a_{3}+mb_3       & b_{3} & c_{3}\\
\end{vmatrix}
=
\begin{vmatrix}
    a_{1}       & b_{1} & c_{1}\\
    a_{2}       & b_{2} & c_{2}\\
    a_{3}       & b_{3} & c_{3}\\
\end{vmatrix}
}
$$


Also, <mark style="background: #FFB86CA6;">GENERALLY</mark> 
$$|A|+|B|\neq |A+B|$$


### Property 6
The value of a determinant is not altered by adding to the elements of any row (or column) the same multiples of the corresponding elements of any other row(or column).

Let,
$$D_1=\begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_{3} \\
\end{vmatrix}$$
and 
$$D_2=\begin{vmatrix}
    a_{1}+ma_2       & b_{1}+mb_2 & c_{1}+mc_3\\
    a_{2}       & b_{2} & c_{2}\\
    a_{3}+na_1       & b_{3}+nb_1 & c_{3}+nc_3\\
\end{vmatrix}
$$
$$\boxed{\text{Then, }D_2=D_1}$$

#### NOTE:
1. When a column (or row) is replaced by one which contains the elements of that column (or row) all multiplied by a number k, then the determinant is multiplied by k. #DIDNTGET
2. When more than one column (or row) is changed by a succession of changes of this kind, at least one column(or row) must be left unaltered.
 <mark style="background: #ADCCFFA6;">Proof:</mark> 
$$\Delta=\begin{vmatrix}
    a_{1}+kb_1       & b_{1}+mc_1 & c_{1}+na_1\\
    a_{2}+kb_2       & b_{2}+mc_2 & c_{2}+na_2\\
    a_{3}+kb_3       & b_{3}+mc_3 & c_{3}+na_3\\
\end{vmatrix}
$$
$$
= \begin{vmatrix}
    a_{1}       & b_{1} & c_{1}\\
    a_{2}       & b_{2} & c_{2}\\
    a_{3}       & b_{3} & c_{3}\\
\end{vmatrix}+
\begin{vmatrix}
kb_1 & mc_1 & na_1 \\
kb_2 & mc_2 & na_2 \\
kb_3 & mc_3 & nc_3 \\
\end{vmatrix}$$

All other determinants such are zero. (Can be checked by expanding everything. "Mat kar lengthy hai")
Hence,

$$\Delta=(1+kmn)\begin{vmatrix}
    a_{1}       & b_{1} & c_{1}\\
    a_{2}       & b_{2} & c_{2}\\
    a_{3}       & b_{3} & c_{3}\\
\end{vmatrix}
$$
Now <mark style="background: #FFB86CA6;">k, m or n has to be zero</mark> for $\Delta$ to have the same value as $\begin{vmatrix}a_{1}       & b_{1} & c_{1}\\ a_{2}       & b_{2} & c_{2}\\ a_{3}       & b_{3} & c_{3}\\ \end{vmatrix}$

3. The presence of 1 as the leading element of $\Delta$ makes it easy to reduce the other elements of the first column to zero.
Example:
$$\Delta=\begin{vmatrix}
1 & 4 & 9 \\
-4& 7 & 25 \\
7& 5 & 2 \\
\end{vmatrix}$$
$$=\begin{vmatrix}
1 & 4 & 9 \\
-4+4(1)& 7+4(4) & 25+4(9) \\
7-7(1) & 5-7(4) & 2-7(9) \\
\end{vmatrix}$$
$$=\begin{vmatrix}
1 & 4 & 9 \\
0 & 23 & 61 \\
0 & -23 & -61 \\
\end{vmatrix}=0$$
