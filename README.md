# forlatext

> 示例
> 
> 技巧：按照0多的那一行（列）展开
> 
> 按第一行展开
>
>$$
\begin{vmatrix}
1&1&2 \\
0&1&0 \\
2&3&5
\end{vmatrix} = 
1 * (-1)^{(1+1)}\begin{vmatrix}
1&0 \\
3&5
\end{vmatrix} + 
1 * (-1)^{(1+2)}\begin{vmatrix}
0&0 \\
2&5
\end{vmatrix} + 
2 * (-1)^{(1+3)}\begin{vmatrix}
0&1 \\
2&3
\end{vmatrix}
>$$
>
> 按第二行展开
>
>$$
\begin{vmatrix}
1&1&2 \\
0&1&0 \\
2&3&5
\end{vmatrix} = 
1 * (-1)^{(2+2)}\begin{vmatrix}
1&2 \\
2&5
\end{vmatrix}
$$

$$
D =
\begin{vmatrix}
1 & 1 & 0 & 3 \\
1 & 1 & 1 & 1 \\
2 & 2 & 3 & 4 \\
5 & 5 & 6 & 6
\end{vmatrix} \qquad
M_{32} = 
\begin{vmatrix}
1 & 0 & 3 \\
1 & 1 & 1 \\
5 & 6 & 6
\end{vmatrix} \qquad
A_{32} = (-1)^{(3+2)}
\begin{vmatrix}
1 & 0 & 3 \\
1 & 1 & 1 \\
5 & 6 & 6
\end{vmatrix}
$$

$$
\begin{vmatrix}
8
\end{vmatrix} = 8 \qquad
\begin{vmatrix}
5
\end{vmatrix} = 5 \qquad
\begin{vmatrix}
-1
\end{vmatrix} = -1
$$

行列式内部元素以 $a_{ij}$表示，i表示行标，j表示列标。

$$
x = \frac{3}{5 * 4-6 * 9} \\qquad
y = \frac{3 * 5-7 * 9}{5 * 4-6 * 9}
$$

$$
x = \frac{3}{5 * 4-6 * 9} \\qquad
y = \frac{3 * 5-7 * 9}{5*4-6 * 9}
$$


##### 第一题
>$$
题目: 求
\begin{vmatrix}
1&2&0&1 \\
2&3&10&0 \\
0&3&5&8 \\
5&10&15&4
\end{vmatrix}
>$$
>
>解: 
>1. 第一行乘以-2，加到第二行，得到: 
>
>$$
\begin{vmatrix}
1&2&0&1 \\
0&-1&10&-2 \\
0&3&5&8 \\
5&10&15&4
\end{vmatrix}
>$$
>
>2. 第一行乘以-5，加到第四行，得到: 
>
>$$
\begin{vmatrix}
1&2&0&1 \\
0&-1&10&-2 \\
0&3&5&8 \\
0&0&15&-1
\end{vmatrix}
>$$
>
>3. 第二行乘以3，加到第三行，得到:
>
>$$
\begin{vmatrix}
1&2&0&1 \\
0&-1&10&-2 \\
0&0&35&12 \\
0&0&15&-1
\end{vmatrix}
>$$
>
>5. 第三行乘以 $-\frac{3}{7}$，加到第四行，得到: 
>$$
    \begin{vmatrix}
1&2&0&1 \\
0&-1&10&-2 \\
0&0&35&12 \\
0&0&0&-\frac{43}{7}
\end{vmatrix}
>$$
>
> 6. 上三角形行列式，结果等于 $1*(-1)*35*(-\frac{43}{7}) = 215$

##### 第二题: 仅仅将第一题中第一列改变
>$$题目: 求
\begin{vmatrix}
8&2&0&1 \\
1&3&10&0 \\
9&3&5&8 \\
3&10&15&4
\end{vmatrix}
>$$
>
>解: 
>1. 因为用8消掉后边行比较麻烦，可以先将第一行，与第二行交换，符号改变。
>2.  因为用8消掉后边行比较麻烦，可以先将第一行，与第二行交换，符号改变。
>3. 再用1，处理第一列，将第一列除去第一行之外都消为0
>4. 再次按照第一题的解法继续

>$$题目: 求
\begin{vmatrix}
1&2&0&1 \\
2&3&10&0 \\
0&3&5&8 \\
5&10&15&4
\end{vmatrix}
$$
>
>abc
>
>sdf


$$
\begin{vmatrix}
0 & 2 & 0 & 0 \\
0 & 0 & 3 & 0 \\
0 & 0 & 0 & 4 \\
1 & 0 & 0 & 0
\end{vmatrix} = (-1)^{N(2341)} 2 * 3 * 4 * 1 = -24
$$

$$
\begin{vmatrix}
8
\end{vmatrix} = 8
\\
\begin{vmatrix}
5
\end{vmatrix} = 5
\\
\begin{vmatrix}
-1
\end{vmatrix} = -1
$$

求解得到：

$$ x = \frac{74-63}{54-69} \qquad y = \frac{35-79}{54-69} $$

可以发现规律： 分子分母，都是两个数的乘积相减（二阶行列式）。 定义新运算（二阶行列式）：



### 性质1: $D^T = D$

取数相乘一定是不同行不同列，第一行取第一列 $a_{11}$，那么第二行就一定不能取第一列，只能取 $a_{22}$，所以最后一行只能取 $a_{nn}$。

##### 符号表示

$$
求
D = \begin{vmatrix}
a_{ij}
\end{vmatrix}
$$


定理2：因为一共有： $n!$个排列，所以排列方式一定是偶数个，而每一种排列，实际上就是将其中2个数对换，每次对换会改变奇偶性，因此各占一半。

dsfadfsa
```math
sdafsadfdf
\begin{bmatrix}
X\\Y
\end{bmatrix}
```

a

$$
题目：求
\begin{cases}
5x+6y=7 \\
9x+4y=3
\end{cases}$$

b

以其中一项: $(-1)^{N(2341)}2 * 7 * 12 * 13$为例，交换之后为: $(-1)^{N(3214)+N(2341)}2 * 7 * 12 * 13$ 。因为交换之后，应用第三种既不按行，也不按列的定义，需要行列的逆序数相加确定符号，可以得到符号改变。重点: 
> 两行互换之后，实际上列标排列没变，行标排列做了一次对换，因此每一项的符号均会发生变化，因此符号改变。


$$
\begin{vmatrix}
a & b\\
c & d
\end{vmatrix} = ad - cb
$$

$
\begin{vmatrix}
a & b\\
c & d
\end{vmatrix} = ad - cb
$


# abc $\frac{1}{2}$

### 性质1: $D^T = D$

>测试行内 $\frac{1}{2}$

$\frac{1}{2}$

测试行内 $\frac{a+b}{c+d}$　

$\frac{a+b}{c+d}$　

测试行内 $\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$

$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.$

题目：求 $
\begin{vmatrix}
8&2&0&1 \\
1&3&10&0 \\
9&3&5&8 \\
3&10&15&4
\end{vmatrix}
$


$
\begin{vmatrix}
8&2&0&1 \\
1&3&10&0 \\
9&3&5&8 \\
3&10&15&4
\end{vmatrix}
$
