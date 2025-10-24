## Uniform circular motion

```tikz
\begin{document}
\begin{tikzpicture}[scale=3, >=stealth]

  % paraméterek
  \def\ang{40} % szög fokban

  % helyvektor komponensei
  \pgfmathsetmacro{\x}{cos(\ang)}
  \pgfmathsetmacro{\y}{sin(\ang)}

  % tengelyek
  \draw[->] (-1.2,0) -- (1.3,0) node[right] {$x$};
  \draw[->] (0,-1.2) -- (0,1.3) node[above] {$y$};

  % egységkör
  \draw (0,0) circle (1);

  % helyvektor
  \draw[very thick,->,blue] (0,0) -- (\x,\y) node[midway,above left] {$\vec r$};

  % sebességvektor (90°-kal elforgatva az r körül)
  \draw[very thick,->,green!60!black] (\x,\y) -- ({\x - \y*0.5},{\y + \x*0.5}) node[right] {$\vec v$};

  % centripetális gyorsulás (a középpont felé mutat)
  \draw[very thick,->,red] (\x,\y) -- ({\x*0.6},{\y*0.6}) node[midway,below right] {$\vec a_c$};

  % pont a körön
  \filldraw[blue] (\x,\y) circle (0.02);

  % szögjelölés
  \draw[->] (0.3,0) arc (0:\ang:0.3) node[midway,right] {$\theta$};

\end{tikzpicture}
\end{document}
```

### Important components 
- kerület: $d = 2 \pi r$ $[m]$
- T 
- f frequecy $[rps]$
- $|\vec{v}|$
- $v =\frac{d}{T}=\frac{2\pi r}{T}$
- $a_{cp} =\frac{2\pi v}{T}n=\frac{4\pi r^{2}}{T^{2}}=\frac{v^{2}}{r}$
- $\vec{F_{cp}}=m a_{cp}$
## Tasks
### Task 1
- $r= 1.5m$
- $v=7\frac{m}{s}$
- $f=?$
- *solution*
	- $f=\frac{1}{T}=\frac{v}{2\pi r}= 7.43\times 10^{-1} rps$
### Task 2 

### Task 4 unit conversation
#### (1)
- $0.002 \frac{km}{h}$
	- $\frac{0.002}{3.6}=$


```tikz
\usepackage{amsmath}
\begin{document}
\begin{tikzpicture} [scale=3, >=stealth]
% Time axis
\draw[->] (0,0) -- (15,0) node[right] {t [s]};
% Velocity axis
\draw[->] (0,0) -- (0,12) node[above] {v [m/s]};
% Velocity function
\draw[thick,blue] (0,0) -- (4,10) -- (8,-5) -- (12,-5) -- (14,0);
% Time marks
\foreach \x in {0,4,8,12,14} \draw (\x,0.2) -- (\x,-0.2) node[below] {\x};
% Velocity marks
\foreach \y in {-5,0,10} \draw (0.2,\y) -- (-0.2,\y) node[left] {\y};
\end{tikzpicture}

\vspace{1cm}

\begin{tikzpicture}[scale=0.7]
% Time axis
\draw[->] (0,0) -- (15,0) node[right] {t [s]};
% Displacement axis
\draw[->] (0,0) -- (0,35) node[above] {s [m]};
% Displacement function
\draw[thick,red] (0,0) -- (4,20) -- (8,30) -- (12,10) -- (14,5);
% Time marks
\foreach \x in {0,4,8,12,14} \draw (\x,0.5) -- (\x,-0.5) node[below] {\x};
% Displacement marks
\foreach \y in {0,10,20,30,35} \draw (0.2,\y) -- (-0.2,\y) node[left] {\y};
\end{tikzpicture}

\vspace{1cm}

\begin{tikzpicture}[scale=0.7]
% Time axis
\draw[->] (0,0) -- (15,0) node[right] {t [s]};
% Acceleration axis
\draw[->] (0,0) -- (0,5) node[above] {a [m/s²]};
% Acceleration function
\draw[thick,green] (0,2.5) -- (4,2.5) -- (4,-3.75) -- (8,-3.75) -- (8,0) -- (12,0) -- (12,2.5) -- (14,2.5);
% Time marks
\foreach \x in {0,4,8,12,14} \draw (\x,0.2) -- (\x,-0.2) node[below] {\x};
% Acceleration marks
\foreach \y in {-4,0,2.5} \draw (0.2,\y) -- (-0.2,\y) node[left] {\y};

\end{tikzpicture}
\end{document}
```
