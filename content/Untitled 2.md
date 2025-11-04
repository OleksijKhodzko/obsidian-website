```tikz
\usepackage{pgfplots}
\pgfplotsset{compat=1.16}

\begin{document}

\begin{tikzpicture}
\begin{axis}[colormap/viridis]
\addplot3[
	surf,
	samples=18,
	domain=-3:3
]
{exp(-x^2-y^2)*x};
\end{axis}
\end{tikzpicture}

\end{document}
```


```tikz
\usepackage{tikz-cd}

\begin{document}
\begin{tikzcd}

    T
    \arrow[drr, bend left, "x"]
    \arrow[ddr, bend right, "y"]
    \arrow[dr, dotted, "{(x,y)}" description] & & \\
    K & X \times_Z Y \arrow[r, "p"] \arrow[d, "q"]
    & X \arrow[d, "f"] \\
    & Y \arrow[r, "g"]
    & Z

\end{tikzcd}

\quad \quad

\begin{tikzcd}[row sep=2.5em]

A' \arrow[rr,"f'"] \arrow[dr,swap,"a"] \arrow[dd,swap,"g'"] &&
  B' \arrow[dd,swap,"h'" near start] \arrow[dr,"b"] \\
& A \arrow[rr,crossing over,"f" near start] &&
  B \arrow[dd,"h"] \\
C' \arrow[rr,"k'" near end] \arrow[dr,swap,"c"] && D' \arrow[dr,swap,"d"] \\
& C \arrow[rr,"k"] \arrow[uu,<-,crossing over,"g" near end]&& D

\end{tikzcd}

\end{document}
```
```tikz
\usetikzlibrary{
    decorations.pathmorphing, % For the curly gluon line
    positioning               % For placing the final label
}

% --- Define the gluon style ---
\tikzset{
    gluon/.style={
        decorate, 
        decoration={snake, segment length=4pt, amplitude=1.5pt}
    }
}

\begin{tikzcd}[
    column sep=4cm, % Adjusts horizontal separation between vertices
    every arrow/.style={thick}, % Makes all lines thicker
    every label/.style={font=\small, inner sep=2pt} % Adjusts label font
]

% 1. Place two main coordinates for the vertices
\coordinate (V1); & \coordinate (V2);

% 2. Draw the external fermion lines
\arrow[from={([xshift=-2.5cm]V1)}, to=(V1), "$p$"] % Incoming 'p'
\arrow[from=(V2), to={([xshift=2.5cm]V2)}, "$p$"] % Outgoing 'p'

% 3. Add the "= \Sigma(p)" label to the right
\node[right=1.2cm of V2] {$= \Sigma(p)$};

% 4. Draw the internal fermion line (bottom)
\arrow[
    from=(V2), to=(V1), % Draw from right to left for the arrow direction
    shorten <=1.5pt, shorten >=1.5pt, % Avoids overlapping vertices
    % --- Labels for the bottom line ---
    % Propagator label
    label={below, pos=0.5, yshift=-15pt: {$\frac{i \delta_{\sigma\tau}}{\rlap{p}+k-m}$}},
    % Right vertex label
    label={below, pos=0.1, yshift=-2pt: {$ig\gamma^\nu T^b_{\tau\beta}$}}, 
    % Left vertex label
    label={below, pos=0.9, yshift=-2pt: {$ig\gamma^\mu T^a_{\alpha\sigma}$}}
]

% 5. Draw the internal gluon loop (top)
\arrow[
    from=(V1), to=(V2), 
    bend left=70, % Sets the arc of the loop
    gluon,        % Applies the curly style
    % --- Labels for the top loop ---
    % Propagator label
    label={above, pos=0.5, yshift=8pt: {$-\frac{i}{k^2} g_{\mu\nu} \delta_{ab}$}},
    % Momentum 'k' label
    "$k$"{description, sloped, pos=0.6}
]

\end{tikzcd}
```

```tikz
\usepackage{amsmath}
\usepackage{tikz-cd}
\usetikzlibrary{
    decorations.pathmorphing, % For the curly gluon line
    positioning               % For placing the final label
}

% --- Define the gluon style ---
\tikzset{
    gluon/.style={
        decorate, 
        decoration={snake, segment length=4pt, amplitude=1.5pt}
    }
}

\begin{tikzcd}[
    column sep=4cm, % Adjusts horizontal separation between vertices
    every arrow/.style={thick}, % Makes all lines thicker
    every label/.style={font=\small, inner sep=2pt} % Adjusts label font
]

% 1. Place two main coordinates for the vertices
\coordinate (V1); & \coordinate (V2);

% 2. Draw the external fermion lines
\arrow[from={([xshift=-2.5cm]V1)}, to=(V1), "$p$"] % Incoming 'p'
\arrow[from=(V2), to={([xshift=2.5cm]V2)}, "$p$"] % Outgoing 'p'

% 3. Add the "= \Sigma(p)" label to the right
\node[right=1.2cm of V2] {$= \Sigma(p)$};

% 4. Draw the internal fermion line (bottom)
\arrow[
    from=(V2), to=(V1), % Draw from right to left for the arrow direction
    shorten <=1.5pt, shorten >=1.5pt, % Avoids overlapping vertices
    % --- Labels for the bottom line ---
    % Propagator label
    label={below, pos=0.5, yshift=-15pt: {$\frac{i \delta_{\sigma\tau}}{\rlap{p}+k-m}$}},
    % Right vertex label
    label={below, pos=0.1, yshift=-2pt: {$ig\gamma^\nu T^b_{\tau\beta}$}}, 
    % Left vertex label
    label={below, pos=0.9, yshift=-2pt: {$ig\gamma^\mu T^a_{\alpha\sigma}$}}
]

% 5. Draw the internal gluon loop (top)
\arrow[
    from=(V1), to=(V2), 
    bend left=70, % Sets the arc of the loop
    gluon,        % Applies the curly style
    % --- Labels for the top loop ---
    % Propagator label
    label={above, pos=0.5, yshift=8pt: {$-\frac{i}{k^2} g_{\mu\nu} \delta_{ab}$}},
    % Momentum 'k' label
    "$k$"{description, sloped, pos=0.6}
]

\end{tikzcd}
```

