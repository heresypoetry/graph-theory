# Chapter 1

## 1.1

### 1.1.1

For this is simple graph, there are at most $\left(\begin{array}{l}n \\ 2\end{array}\right)$ edges there, when every 2 verticals are connected. That is, when this graph is a complete graph.

### 1.1.2

(a) The situation with the. most edges is that conenect every vertical in $X$ and every vertical in $Y$, which contains $rs$ edges. So there are $m \leq rs$. 

(b)

(c)

### 1.1.3

(a) Choose any vertical $x_0$ in this path. $X:= \{ y \ in \ the \ path\ s.t \ distance(x_0,y) \ is \ odd   \}$, $Y:= \{ y \ in \ the \ path\ s.t \ distance(x_0,y) \ is \ even   \}\cup\{ x_0\} $. So verticals in $X$ do not connected with each other, so did $Y$, and $X \cup Y$ is equal to all verticals in this path. So every path is the bipartite. 

(b) 

### 1.1.4

$$\delta(G) = \frac{1}{|V|}\sum_{v \in V}\delta(G) \leq d(G)= \frac{1}{|V|}\sum_{v \in V}d(v) \leq \frac{1}{|V|}\sum_{v \in V}\Delta(G) = \Delta(G) $$ 

### 1.1.5

When $k = 0$, the 0-regular graph is graph such that $E = \empty$. 

when $k=1$, for vertical in V denoted with $\{v_1,\dots,v_n\}$, for $v_1$, there is exact a verticle connected with it ,assume $v_2$,  then $v_2$ is not connected with any other verticles. This is the same for all verticals. So n must be even and there must be $\frac{n}{2}$ pairs of verticles connected only wiith each other. So this is a bipartite. 

when $k =2$,  this is a cycle. for vertical in V denoted with $\{v_1,\dots,v_n\}$. for $v_1$, there exist an element, assume $v_2$, which connected with $v_1$. Because there are exactly 2 verticles connected with    



### 1.1.6

