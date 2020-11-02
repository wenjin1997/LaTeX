# LaTeX学习笔记
### 书籍信息
书名：《LaTeX2e完全学习手册》

作者：胡伟 

出版社：清华大学出版社, 2011.1
### 笔记
* 在编译源文件时，LaTeX将忽略命令之后的所有空格，如果希望在命令后保留一个空格，
可在命令后紧跟一对空花括号{}和一个空格，或在命令后紧跟一个反斜杠\和一个空格。

### 展示方程组
如果要展示方程组，则可以放在case中，如下所示。同时一定要调用宏包amsmath。
```
\begin{equation} \label{eq_arry}%要调用宏包amsmath
	\begin{cases}
		{f}_1({x}_1,{x}_2,\cdots,{x}_n)=0\\
		{f}_2({x}_1,{x}_2,\cdots,{x}_n)=0\\
		\qquad \qquad \vdots\\
		{f}_n({x}_1,{x}_2,\cdots,{x}_n)=0
	\end{cases}	
\end{equation}
```
