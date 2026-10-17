#def
>[!abstract] Definizione
>Sia $f:A \subseteq \mathbb{R}^d \to \mathbb{R}$
>Sia $x_{0}$ un [[Punto di Accumulazione]] di $A$
>Sia $l \in \mathbb{R}$
>Si dice che
>$$\lim_{ x \in A \to x_{0} }f(x)=l$$
>Se:
>$$
>\forall \epsilon>0 ~ \exists \delta>0~ t.c.~ d(x; x_{0})<\delta~ \text{(ovvero: } x \in B_{\delta}(x_{0}) \text{)}~ \implies |f(x)-l|<\epsilon
>$$


#prop
> [!quote] Proposizione
> Sia: 
> $$
\lim_{ (x, y) \to (x_{0}, y_{0}) } f(x, y) = l$$
Sia:$$
\begin{cases}
x(t) = x_{0} + \alpha t \\
y(y) = y_{0} + \beta t \\
\end{cases}$$
allora: 
>$$
>\lim_{ t \to 0 } f(x_{0}+\alpha t, y_{0}+\beta t) = l 
>$$

#dim
Per ipotesi:
$$
\lim_{ x,y \to (x_{0}, y_{0}) } f(x, y)=l 
$$
implica che:
$\forall \epsilon>0, \exists \delta>0$ tale che :
se 
	la distanza di un punto qualsiasi $P=(x, y)$ nel dominio, dal punto $(x_{0}, y_{0})$ è inferiore a $\delta$:
$$
0<\sqrt{ (x-x_{0})^2 +(y-y_{0})^2}<\delta \tag{1}
$$
allora:
	la distanza dell'immagine di $P$ dal valore del limite $l$, è inferiore all'$\epsilon$:
$$
0<|f(x, y)-l|<\epsilon
$$

Ora consideriamo una generica retta passante per il punto $(x_{0}, y_{0})$, parametrizzata a $t$, e con verso: $\vec{v}=(\alpha, \beta)$.
I punti di questa retta sono netta forma $(x(t), y(t))$:
$$
\begin{cases}
x(t) = x_{0}+\alpha t \\
y(t) = y_{0}+\beta t
\end{cases}
$$
Ora ci chiediamo quanto dista questo punto $P=(x(t), y(t))$ dal punto $P_{0}=(x_{0}, y_{0})$:
$$
d(P, P_{0})=\sqrt{ (x_{0}+\alpha t-x_{0})^2 +(y_{0}+\beta t-y_{0})^2}
$$
$$
=\sqrt{ (\alpha t)^2+(\beta t)^2 }=|t|\cdot \sqrt{ \alpha^2+\beta^2 }
=|t|\cdot K
$$
Ora sfruttiamo l'ipotesi: 
sappiamo che esiste un certo $\delta$ tale che se la distanza di un punto $P$ da $P_{0}$ è inferiore a questo $\delta$, allora l'immagine dista da $l$ meno di un certo $\epsilon$.
Questo $\delta$ esiste, si procede a trovare per quali $t$, la distanza $d(P, P_{0})<\delta$
$$
d(P, P_{0})=|t|\cdot K<\delta
$$
$$
\implies |t| < \frac{\delta}{K}
$$



la funzione $f$, calcolata lungo questa retta sarà:
$$
f(x(t), y(t))=f(x_{0}+\alpha t, y_{0}+\beta y)
$$
calcolando il limite per $t\to{0}$:
$$
\lim_{ t \to 0 } f(x(t), y(t))=l 
$$
si deve dimostrare che:
$\forall \epsilon>0, \exists \mu >0$ tale che:
se:
	la distanza da un qualsiasi sulla retta t, dal punto $t=0$, è inferiore a $\mu$:
	
$$
0<|t-0|<\mu \tag{2}
$$
allora:
	la distanza dall'immagine di questo punto $t$, dal valore del limite $l$, è inferiore a $\epsilon$:
	
$$
0<|f(x_{0}+\alpha t; y_{0}+\beta t)-l|<\epsilon
$$

Per dimostrarlo calcoliamo la distanza da un generico punto sulla retta $(x(t), y(y))$ dal punto $(x_{0}, y_{0})$:
$$
d(P, P_{0})=\sqrt{ (x_{0}+\alpha t-x_{0})^2 +(y_{0}+\beta t-y_{0})^2}
$$
$$
=\sqrt{ (\alpha t)^2+(\beta t)^2 }=|t|\cdot \sqrt{ \alpha^2+\beta^2 }
=|t|\cdot K
$$
dall'ipotesi iniziale $(1)$ sappiamo che esiste un certo $\delta$, dobbiamo garantire che la distanza del punto sulla retta da $(x_{0}, y_{0})$ sia minore di $\delta$:
$$
|t|\cdot K < \delta \implies |t|< \frac{\delta}{K}
$$
si definisce $\mu=\frac{\delta}{K}$
A questo punto si osserva che se si prende un $t$ tale che $0<t<\mu$, allora la distanza del punto sulla retta da $(x_{0}, y_{0})$ è inferiore a $\delta$, e poiche la distanza è inferiore a $\delta$ questo assicura che il valore dell

