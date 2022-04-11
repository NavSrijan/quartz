# Determinants
Determinants can only be found of <mark style="background: #FFB8EBA6;">square matrices</mark> .

$$
\begin{vmatrix}
    a_{11}       & a_{12} & a_{13}\\
    a_{21}       & a_{22} & a_{23}\\
    a_{31}       & a_{32} & a_{33}\\
\end{vmatrix}
$$
###### <u>Deciding the sign of the argument</u>
If the sum of the digits of the subscript is:
- Even ---> +ve
- Odd ---> -ve

Example: $a_{11}(a_{22}\times a_{33}-a_{23}\times a_{32})$ is <mark style="background: #D2B3FFA6;">positive</mark> since in $a_{11}\,$, $1+1=2$ which is <mark style="background: #ADCCFFA6;">even</mark> .

$a_{12}(a_{21}\times a_{33}-a_{23}\times a_{31})$ is <mark style="background: #D2B3FFA6;">negative</mark> since in $a_{12}\,$, $1+2=3$ which is <mark style="background: #ADCCFFA6;">odd</mark> .

# Expansion of Determinant

### Order 2:
$$A=\begin{vmatrix}
a & b \\
c & d \\
\end{vmatrix}$$
$$\boxed{det \,A = ad-bc}$$

### Order 3:
$$B=\begin{vmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{vmatrix}$$
$$\boxed{det \,B = a_{11}(a_{22}\, a_{33} - a_{23}\, a_{32})-a_{12}(a_{21}\, a_{33} - a_{23}\, a_{31})+a_{12}(a_{21}\, a_{32} - a_{22}\, a_{31})}$$


$$\begin{vmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33} \\
\end{vmatrix}=
a_{11} \begin{vmatrix} 
    a_{22} & a_{23} \\
    a_{32} & a_{33} \\
\end{vmatrix}
-a_{12}
\begin{vmatrix} 
    a_{21} & a_{23} \\
    a_{31} & a_{33} \\
\end{vmatrix}
+a_{31} \begin{vmatrix} 
    a_{21} & a_{22} \\
    a_{31} & a_{32} \\
\end{vmatrix}
$$

## NOTE
1. Area of a triangle whose vertices are ($x_{r}, y_r$); r =1,2,3 is:
$$D=\frac{1}{2}\begin{vmatrix}
x_{1} & y_1 & 1 \\
x_2 & y_2 & 1 \\
x_3 & y_3 & 1 \\
\end{vmatrix}$$
<mark style="background: #FF5582A6;">If D=0 then three points are collinear.</mark> 
Question: [[Questions#Area Of Triangle|QUESTIONS]]
1. Equation of a straight line passing through $(x_{1}, y_{1})$ and $(x_{2}, y_2)$ is:
$$\begin{vmatrix}
x & y & 1 \\
x_1 & y_1 & 1 \\
x_2 & y_2 & 1 \\
\end{vmatrix}=0$$
1. The lines: 
$a_{1}x+b_{1}y+c_{1}=0$
$a_{2}x+b_{2}y+c_{2}=0$
$a_{3}x+b_{3}y+c_{3}=0$

are concurrent if, $$\begin{vmatrix}
a_{1}  & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3 \\
\end{vmatrix}=0$$

1. $ax^2+2hxy+by^2+2gx+2fy+c=0$ represents a pair of straight line if
$$\boxed{abc+2fgh-af62-bg^2-ch^2=0=\begin{vmatrix}
a & h & g \\
h & b & f \\
g & f & c \\
\end{vmatrix}}$$