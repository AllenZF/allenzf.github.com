<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
# MathJax 常用公式、符号参考手册
* LaTeX-2种使用形式
    * 行内使用：
        * 文本：`$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt$`
        * 效果：$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt$
    * 单独成行：
        * 文本：`$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt$$`  
        * 效果（文本前有一行空行）： 

$$\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt$$  
## 一、希腊字母  
| 名称 | 大写 | Tex | 小写 | Tex|
| :-: | :-: | :-: | :-: | :-: | 
| alpha |$\Alpha$| \Alpha |   $\alpha$ | \alpha |
| beta|$\Beta$|\Beta|$\beta$|\beta|
| gamma | $\Gamma$|\Gamma|$\gamma$|\gamma|
|delta|$\Delta$|\Delta|$\delta$|\delta|
|epsilon|$\Epsilon$|\Epsilon|$\epsilon$|\epsilon|
|zeta|$\Zeta$|\Zeta|$\zeta$|\zeta|
|eta|$\Eta$|\Eta|$\eta$|\eta|
|theta|$\Theta$|\Theta|$\theta$|\theta|
|iota|$\Iota$|\Iota|$\iota$|\iota|
|kappa|$\Kappa$|\Kappa|$\kappa$|\kappa|
|lambda|$\Lambda$|\Lambda|$\lambda$|\lambda|
|mu|$\Mu$|\Mu|$\mu$|\mu|
|nu|$\Nu$|\Nu|$\nu$|\nu|
|xi|$\Xi$|\Xi|$\xi$|\xi|
|omicron|$\Omicron$|\Omicron|$\omicron$|\omicron|
|pi|$\Pi$|\Pi|$\pi$|\pi|
|rho|$\Rho$|\Rho|$\rho$|\rho|
|sigma|$\Sigma$|\Sigma|$\sigma$|\sigma|
|tau|$\Tau$|\Tau|$\tau$|\tau|
|upsilon|$\Upsilon$|\Upsilon|$\upsilon$|\upsilon|
|phi|$\Phi$|\Phi|$\phi$|\phi|
|chi|$\Chi$|\Chi|$\chi$|\chi|
|psi|$\Psi$|\Psi|$\psi$|\psi|
|omega|$\Omega$|\Omega|$\omega$|\omega|   

# 二、上下标  

| 语法（省略$$） | 效果 |
| :-: | :-:|
| x_i^2 |$x_i^2$|
| x^2_i |$x^2_i$|
| {x_i}^2 |${x_i}^2$|
|x_{i^2} |$x_{i^2}$|
| x_i_2 |error|
| x_{i_2} |$x_{i_2}$|
| x^i^2 |error|
| x^{i^2} |$x^{i^2}$|  
| \hat {x}|$\hat {x}$|
| \widehat {xy}|$\widehat {xy}$|
| \overline {x}| $\overline {x}$|
| \overline {x+y}| $\overline {x+y}$|
| \underline {x}| $\underline {x}$|
| \underline {x+y}| $\underline {x+y}$|
| \vec {x}|$\vec {x}$|
| \dot {x}|$\dot {x}$|
| \ddot {x}|$\ddot {x}$|


# 三、 括号   

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| (2+3)|$(2+3)$|
| [2+3]|$[2+3]$|
| `\{x\}` |$\{x\}$|
|\lbrace x \rbrace|$\lbrace x \rbrace$|
|\langle x \rangle|$\langle x \rangle$|尖括号|
|\lceil x \rceil|$\lceil x \rceil$|上取整|
|\lfloor x \rfloor|$\lfloor x \rfloor$|下取整|  

# 四、关系运算

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| \pm |$\pm$|
| \times |$\times$|
| \div |$\div$|
| \mid |$\mid$|
| \cdot |$\cdot$|$a\cdot b$|
| \cdots|$\cdots$|$a\cdots b$|
| \ldots|$\ldots$|$a\ldots b$|
| \ast |$\ast$|
| \lt |$\lt$|
| \leq 或 \le |$\leq$|
| \not\lt|$\not\lt$|
| \gt |$\gt$|
| \geq 或 \ge|$\geq$|
| \not\gt|$\not\gt$|
| \neq 或 \ne|$\neq$|
| \approx |$\approx$|
| \appromd|$\approx$||
| \equiv |$\equiv$|
| \sim |$\sim$|
| \cong |$\cong$|
| \prec|$\prec$|
| \not | $\not$ |
| \star|$\star$|
| \ast |$\ast$|
| oplus|$\oplus$|
| \bullet|$\bullet$|
| \circ|$\circ$|


# 五、集合运算

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| \varnothing |$\varnothing$|空|
| \emptyset |$\emptyset$|空集|
| \notin |$\notin$|不属于|
| \in |$\in$|属于|
| \subset |$\subset$|真子集|
| \subseteq |$\subsetneq$|真子集|
| \subseteq |$\subseteq$|子集|
| \supset |$\supset$|父集|
| \supseteq |$\supseteq$|父集|
| \cap |$\cap$|交集|
| \bigcap |$\bigcap$|交集|
| \cup |$\cup$|并集|
| \bigcup |$\bigcup$|并集|
| \bigvee |$\bigvee$|
| \bigwedge |$\bigwedge$|


# 六、微积分运算

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| \prime |$\prime$|微分|
| \int |$\int$|
| \iint |$\iint$|
| \iiint |$\iiint$|
| \oint |$\oint$|
| \lim |$\lim$|
| \lim_{x\rightarrow +\infty}|$\lim_{x\rightarrow +\infty}$|
| \lim\limits_{x\rightarrow+\infty}|$\lim\limits_{x\rightarrow+\infty}$|
| \lim\nolimits_{x\rightarrow+\infty}|$\lim\nolimits_{x\rightarrow+\infty}$|
| \infty |$\infty$|
| \nabla |$\nabla$|
| \prod|$\prod$|
| \sum|$\sum$|
| \sum_{k=1}^n{kx}|$\sum_{k=1}^n{kx}$|
| \sum\limits_{k=1}^n{kx}|$\sum\limits_{k=1}^n{kx}$|
| \sum\nolimits_{k=1}^n{kx}|$\sum\nolimits_{k=1}^n{kx}$|
| \aleph|$\aleph$|
| \partial|$\partial$|
| \Im |$\Im$|
| \Re|$\Re$|


# 七、逻辑运算  

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| \because |$\because$|因为|
| \therefore |$\therefore$|所以|
| \forall |$\forall$|任意|
| \exists |$\exists$|存在|
| \land | $\land$ | 与 |
| \lor | $\lor$ | 或 |
| \lnot |$\lnot$ | 非|
| \top | $\top$ |
| \bot | $\bot$ |
| \vdash | $\vdash$ |
| \vDash |$\vDash$|

# 八、箭头符号  

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| \uparrow |$\uparrow$|
| \Uparrow |$\Uparrow$|
| \downarrow |$\downarrow$|
| \Downarrow |$\Downarrow$|
| \leftarrow |$\leftarrow$|
| \Leftarrow |$\Leftarrow$|
| \rightarrow |$\rightarrow$|
| \Rightarrow |$\Rightarrow$|
| \to |$\to$|
| \mapsto|$\mapsto$|

# 九、 分式、根式

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| \frac ab |$\frac ab$|
| \frac {a}{b} |$\frac {a}{b}$|标准|
| {a+1 \over b+1}|$a+1 \over b+1$|
| \sqrt[4]{\frac xy} |$\sqrt[4]{\frac xy}$|

* 连分式  
    * 书写：`x = a_0 + \frac {1^2}{a_1 +\frac {2^2}{a_3 + ...}}`  
    * 效果：   

    $$x = a_0 + \frac {1^2}{a_1 +\frac {2^2}{a_3 + ...}}$$
    * 书写：`x = a_0 + \cfrac {1^2}{a_1 +\cfrac {2^2}{a_3 + ...}}`  
    * 效果($\color{lime}{推荐}$)：   

    $$x = a_0 + \cfrac {1^2}{a_1 +\cfrac {2^2}{a_3 + ...}}$$


# 十、多行表达式

&emsp;&emsp;通用语法：`\begin{cases}...\end{cases}`,常使用`\\`来分类，使用`&`来对其，用`\空格`表示空格。

## 分类表达式  

* 书写：
```
$$
f(n)
\begin{cases}
\cfrac n2, &if\ n\ is\ even\\
3n + 1, &if\ n\ is\ odd
\end{cases}
$$
```
* 效果：  

$$
f(n)
\begin{cases}
\cfrac n2, &if\ n\ is\ even\\
3n + 1, &if\ n\ is\ odd
\end{cases}
$$

&emsp;&emsp;如果想分类之间的垂直间隔变大，可使用`\\[2ex]`代替`\\`来分隔不同的情况。（1ex:原始距离。3ex,4ex都可以）  

$$
f(n)
\begin{cases}
\cfrac n2, &if\ n\ is\ even\\[2ex]
3n + 1, &if\ n\ is\ odd
\end{cases}
$$

* 书写：
```
$$
\begin{aligned}
y &= (a+b)^2\\
  &= a^2 +b^2 +2ab\\
  &= 0
\end{aligned}
$$
```
* 效果：  

$$
\begin{aligned}
y &= (a+b)^2\\
  &= a^2 +b^2 +2ab\\
  &= 0
\end{aligned}
$$

## 方程组 
&emsp;&emsp;使用`\begin{array}...\end{array}`与`\left \{`与`\right.`配合表示方程组  
* 书写：
```
$$
\left \{ 
\begin{array}{c}
a_1x+b_1y+c_1z=d_1 \\ 
a_2x+b_2y+c_2z=d_2 \\ 
a_3x+b_3y+c_3z=d_3
\end{array}
\right .
$$
或
$$
\begin{cases}
a_1x+\ b_1y+\quad c_1z=d_1 \\ 
a_2x+\;b_2y+\qquad c_2z=d_2 \\ 
a_3x+b_3y+c_3z=d_3
\end{cases}
$$
```
* 效果1：  

$$
\left \{ 
\begin{array}{c}
a_1x+b_1y+c_1z=d_1 \\ 
a_2x+b_2y+c_2z=d_2 \\ 
a_3x+b_3y+c_3z=d_3
\end{array}
\right .
$$
* 效果2：  

$$
\begin{cases}
a_1x+\ b_1y+\quad c_1z=d_1 \\ 
a_2x+\;b_2y+\qquad c_2z=d_2 \\ 
a_3x+b_3y+c_3z=d_3
\end{cases}
$$
**注意**：通常MathJax通过内部策略自己管理公式内部的空间，因此a…b与a……b（.表示空格）都会显示为ab。可以通过在ab间加入`\空格`,增加些许间隙，`\;`增加较宽的间隙，`\quad `与 `\qquad `会增加更大的间隙。  

# 十一、特殊函数
## 三角函数

| 语法（省略$$） | 效果 |说明|
| :-: | :-:|:-:|
| \sin x|$\sin x$|
| \arctan x|$\arctan x$|

# 十二、矩阵

&emsp;&emsp;使用`\begin{matrix}…\end{matrix}`这样的形式来表示矩阵，在`\begin`与`\end`之间加入矩阵中的元素即可。矩阵的行之间使用`\\`分隔，列之间使用`&`分隔。使用`\cdots`$\cdots$,`\ddots`$\ddots$,`\vdots` $\vdots$ ,来省略矩阵中的元素。

* 书写：   
```
$$
\begin{matrix}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23} \\
x_{31} & x_{32} & x_{33}
\end{matrix}
$$
```

* 效果1：**matrix**   

$$
\begin{matrix}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23} \\
x_{31} & x_{32} & x_{33}
\end{matrix}
$$


* 效果2：**pmatrix**或 `\left(...\right)`   

$$
\begin{pmatrix}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23} \\
x_{31} & x_{32} & x_{33}
\end{pmatrix}
$$


* 效果3：**bmatrix**或 `\left[...\right]`    

$$
\begin{bmatrix}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23} \\
x_{31} & x_{32} & x_{33}
\end{bmatrix}
$$

* 效果4：**Bmatrix**或`\left\{...\right\}`   

$$
\begin{Bmatrix}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23} \\
x_{31} & x_{32} & x_{33}
\end{Bmatrix}
$$

* 效果5：**vmatrix**   

$$
\begin{vmatrix}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23} \\
x_{31} & x_{32} & x_{33}
\end{vmatrix}
$$

* 效果6：**Vmatrix**   

$$
\begin{Vmatrix}
x_{11} & x_{12} & x_{13} \\
x_{21} & x_{22} & x_{23} \\
x_{31} & x_{32} & x_{33}
\end{Vmatrix}
$$
* 矩阵中的省略号  
```
$$
\begin{pmatrix}
1&a_1&a_1^2&\cdots&a_1^n\\
1&a_2&a_2^2&\cdots&a_2^n\\
\vdots&\vdots&\vdots&\ddots&\vdots\\
1&a_m&a_m^2&\cdots&a_m^n\\
\end{pmatrix}
$$
```
$$
\begin{pmatrix}
1&a_1&a_1^2&\cdots&a_1^n\\
1&a_2&a_2^2&\cdots&a_2^n\\
\vdots&\vdots&\vdots&\ddots&\vdots\\
1&a_m&a_m^2&\cdots&a_m^n\\
\end{pmatrix}
$$
* 增广矩阵
```
$$
\left[
\begin{array}{cc|c}
1&2&3\\
4&5&6
\end{array}
\right]
$$
```
$$
\left[
\begin{array}{cc|c}
1&2&3\\
4&5&6
\end{array}
\right]
$$
# 十三、表格
&emsp;&emsp;使用`\begin{array}{列样式}…\end{array}`这样的形式来创建表格，列样式可以是`c l r`表示居中，左，右对齐，还可以使用`|`表示一条竖线。表格中各行使用`\\`分隔，各列使用`&`分隔。使用`\hline`在本行前加入一条直线。
* 书写：  
```
$$
\begin{array}{c|lcr}
n & \text{Left} & \text{Center} & \text{Right} \\
\hline
1 & 0.24 & 1 & 125 \\
2 & -1 & 189 & -8 \\
3 & -20 & 2000 & 1+10i \\
\end{array}
$$
```
$$
\begin{array}{c|lcr}
n & \text{Left} & \text{Center} & \text{Right} \\
\hline
1 & 0.24 & 1 & 125 \\
2 & -1 & 189 & -8 \\
3 & -20 & 2000 & 1+10i \\
\end{array}
$$

# 十四、字体
1. **黑板粗体**：此字体经常用来表示代表实数、整数、有理数、复数的大写字母。  
`\mathbb {ALLEN} `:$\quad\mathbb {ALLEN}$  
`\Bbb {ALLEN} `:$\quad\Bbb {ALLEN}$
2. **黑体**:  
`\mathbf {ALLEN} `:$\quad\mathbf {ALLEN}$    
3. **打印机字体**:  
`\mathtt {ALLEN} `:$\quad\mathtt {ALLEN}$  
4. **罗马字体**：  
`\mathrm {ALLEN} `:$\quad\mathrm {ALLEN}$   
5. **手写体**:  
`\mathscr {ALLEN} `:$\quad\mathscr {ALLEN}$     

# 十五、 颜色
&emsp;&emsp;`\color{black}{text} `：$\color{black}{text}$  
&emsp;&emsp;`\color{gray}{text} `：$\color{gray}{text}$  
&emsp;&emsp;`\color{silver}{text} `:$\color{silver}{text}$  
&emsp;&emsp;`\color{white}{text} `:$\color{white}{text}$  
&emsp;&emsp;`\color{maroon}{text} `:$\color{maroon}{text}$  
&emsp;&emsp;`\color{red}{text} `:$\color{red}{text}$  
&emsp;&emsp;`\color{yellow}{text} `:$\color{yellow}{text}$    
&emsp;&emsp;`\color{lime}{text} `:$\color{lime}{text}$  
&emsp;&emsp;`\color{olive}{text} `:$\color{olive}{text}$  
&emsp;&emsp;`\color{green}{text} `:$\color{green}{text}$  
&emsp;&emsp;`\color{teal}{text} `:$\color{teal}{text}$  
&emsp;&emsp;`\color{aqua}{text} `:$\color{aqua}{text}$  
&emsp;&emsp;`\color{blue}{text} `:$\color{blue}{text}$  
&emsp;&emsp;`\color{navy}{text} `:$\color{navy}{text}$  
&emsp;&emsp;`\color{purple}{text} `:$\color{purple}{text}$  
&emsp;&emsp;`\color{fuchsia}{text} `:$\color{fuchsia}{text}$  

