# Haferman Carpet Fractal Generator

Generate and explore the Haferman carpet, a generalization of the Sierpiński carpet, with configurable hole pattern, depth, and colors.

## Features
- 9 preset hole patterns including Sierpiński, Cross, Cantor, Corners, H-shape
- Interactive 3×3 custom pattern editor — click cells to toggle holes
- Depth slider from 1 to 6 with live render performance timing
- Fill and background color pickers
- Fractal dimension (Hausdorff) computed from log(filled)/log(3)
- PNG download button
- Educational panel explaining fractal dimension and Sierpiński generalization

## Usage
1. Select a preset pattern or click cells in the Custom Pattern grid
2. Adjust depth (warning: depth 6 is CPU-intensive)
3. Change fill/background colors for visual variety
4. Click Download PNG to save the result

## Tech
- Tailwind CSS CDN
- Vanilla JS / Canvas API (recursive drawHaferman function)
