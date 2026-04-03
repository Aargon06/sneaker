# sneaker — A configurable TikZ sneaker drawing

A LaTeX package that provides a highly configurable sneaker
illustration using TikZ. The shoe can be customised via a
key–value interface: colours, laces, velcro straps, eyelets,
decorative patterns (bolt or star), stitching, and rolling
wheels are all available as simple options.

## Usage
```latex
\usepackage{sneaker}

\begin{tikzpicture}
  \pic{sneaker={color=red, laces=true, eyelets=true, stitching=true}};
\end{tikzpicture}
```

## Requirements

- LaTeX2e
- TikZ with library `calc`

## License

LPPL 1.3c — see `sneaker-doc.pdf` for full details.