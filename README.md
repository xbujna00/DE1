| **Dec. equivalent** | **B[1:0]** | **A[1:0]** | **B is greater than A** | **B equals A** | **B is less than A** |
| :-: | :-: | :-: | :-: | :-: | :-: |
 | 0 | 0 0 | 0 0 | 0 | 1 | 0 |
 | 1 | 0 0 | 0 1 | 0 | 0 | 1 |
 | 2 | 0 0 | 1 0 | 0 | 0 | 1 |
 | 3 | 0 0 | 1 1 | 0 | 0 | 1 |
 | 4 | 0 1 | 0 0 | 1 | 0 | 0 |
 | 5 | 0 1 | 0 1 | 0 | 1 | 0 |
 | 6 | 0 1 | 1 0 | 0 | 0 | 1 |
 | 7 | 0 1 | 1 1 | 0 | 0 | 1 |
 | 8 | 1 0 | 0 0 | 1 | 0 | 0 |
 | 9 | 1 0 | 0 1 | 1 | 0 | 0 |
 | 10 | 1 0 | 1 0 | 0 | 1 | 0 |
 | 11 | 1 0 | 1 1 | 0 | 0 | 1 |
 | 12 | 1 1 | 0 0 | 1 | 0 | 0 |
 | 13 | 1 1 | 0 1 | 1 | 0 | 0 |
 | 14 | 1 1 | 1 0 | 1 | 0 | 0 |
 | 15 | 1 1 | 1 1 | 0 | 1 | 0 |
 
 
 <a href="https://www.codecogs.com/eqnedit.php?latex=\begin{align*}&space;grater_{min.}^{SOP}&space;=&space;(\overline{b_{1}}\&space;\cdot&space;a_{1})&space;&plus;(&space;b_{1}&space;\cdot&space;b_{0}&space;\cdot&space;\overline{a_{0}}\)&space;&plus;&space;(b_{0}&space;\cdot&space;\overline{a_{1}}\&space;\cdot&space;\overline{a_{0}}\)\\&space;less_{min.}^{POS}&space;=&space;(\overline{b_{1}}\&space;&plus;&space;a_{1})&space;\cdot&space;(\overline{b_{0}}&space;&plus;&space;\cdot&space;a_{1})&space;\cdot&space;(\overline{b_{1}}\&space;&plus;&space;\overline{b_{0}}\&space;)&space;\cdot&space;(a_{1}&space;&plus;&space;a_{0})&space;\cdot&space;(\overline{b_{1}}\&space;&plus;&space;a_{0})&space;\\&space;\end{align*}" target="_blank"><img src="https://latex.codecogs.com/png.latex?\begin{align*}&space;grater_{min.}^{SOP}&space;=&space;(\overline{b_{1}}\&space;\cdot&space;a_{1})&space;&plus;(&space;b_{1}&space;\cdot&space;b_{0}&space;\cdot&space;\overline{a_{0}}\)&space;&plus;&space;(b_{0}&space;\cdot&space;\overline{a_{1}}\&space;\cdot&space;\overline{a_{0}}\)\\&space;less_{min.}^{POS}&space;=&space;(\overline{b_{1}}\&space;&plus;&space;a_{1})&space;\cdot&space;(\overline{b_{0}}&space;&plus;&space;\cdot&space;a_{1})&space;\cdot&space;(\overline{b_{1}}\&space;&plus;&space;\overline{b_{0}}\&space;)&space;\cdot&space;(a_{1}&space;&plus;&space;a_{0})&space;\cdot&space;(\overline{b_{1}}\&space;&plus;&space;a_{0})&space;\\&space;\end{align*}" title="\begin{align*} grater_{min.}^{SOP} = (\overline{b_{1}}\ \cdot a_{1}) +( b_{1} \cdot b_{0} \cdot \overline{a_{0}}\) + (b_{0} \cdot \overline{a_{1}}\ \cdot \overline{a_{0}}\)\\ less_{min.}^{POS} = (\overline{b_{1}}\ + a_{1}) \cdot (\overline{b_{0}} + \cdot a_{1}) \cdot (\overline{b_{1}}\ + \overline{b_{0}}\ ) \cdot (a_{1} + a_{0}) \cdot (\overline{b_{1}}\ + a_{0}) \\ \end{align*}" /></a>

## 2. 2-bit comparator 

### The K-map for the "equals" function is as follows:

![Kmap1](mapa.png)

### The K-map for the "less" function is as follows:

![Kmap2](mapa1.png)


**rovnica:**
 
*  (B̅1+A1)*(B̅0+A1)*(B̅1+B̅0)*(A1+A0)*(B̅1+A0) * 




### The K-map for the "grater" function is as follows:


![Kmap2](mapa2.png)
