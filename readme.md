# CSS vs SVG Gradient Comparison 🌈

A simple demonstration comparing gradient transitions using CSS and SVG implementations.

## Purpose 🎯
Observe visual and performance differences between CSS-based and SVG-based color gradients during scroll-triggered transitions.

## How It Works ⚙️
- **Vertical scroll** triggers gradient phase changes
- **Left panel**: CSS `linear-gradient` with layered opacity transitions
- **Right panel**: SVG `<linearGradient>` with direct color updates

## Key Differences 🔍
| Feature        | CSS                          | SVG                    |
|----------------|------------------------------|------------------------|
| **Rendering**  | Layered opacity animation    | Direct color changes   |
| **Smoothness** | Gradual fade between layers  | Instant color updates  |
| **Complexity** | Multiple stacked elements    | Single SVG element     |


## Demo 🚀
You can test the project online at: [css-vs-svg]()

## License 📄
MIT License - Free for use and modification