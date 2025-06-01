# BlockDAG Visualizer

An interactive simulation of a BlockDAG (Directed Acyclic Graph) network, inspired by Kaspa.  
This visualizer demonstrates real-time block generation, parent-child connectivity, tip set evolution, and dynamic layout behavior.

## Features

- Real-time block simulation with configurable BPS (blocks per second)
- Multiple parent selection for each block
- Dynamic tip set handling
- Smooth scrolling and zoom controls
- Toggleable block labels and connection lines
- Randomized burst timing and jitter for natural-looking variation
- Grid-based layout with collision avoidance

## Technologies

- D3.js v7
- Pure HTML/CSS/JS
- Works entirely in-browser (no backend needed)

## Live Demo

Try it out here:  
https://PlotTwistDev.github.io/blockdag-visualizer

## Deployment (GitHub Pages)

1. Push the contents of this repository to your GitHub account.
2. Go to your repository settings.
3. Navigate to the "Pages" section.
4. Select the `main` branch and `/root` folder (or `/docs` if applicable).
5. Click "Save".

Your visualization will be live at:  
`https:/PlotTwistDev.github.io/blockdag-visualizer`

## Installation

Clone the repo:

```bash
git clone https://github.com/PlotTwistDev/blockdag-visualizer.git
cd blockdag-visualizer
```

Open `index.html` in your browser:

```bash
open index.html
# or simply double-click it
```

## Usage

- Target BPS – adjust how many blocks are generated per second.
- Zoom Controls – zoom in/out using the HUD buttons or mouse wheel.
- HUD Toggles – show/hide block labels and connection lines.
- Reset – clears the graph and resets the simulation.

## File Structure

```
blockdag-visualizer/
├── index.html       # Main HTML file
├── README.md        # This file
```

## Credits

This project is inspired by Kaspa’s BlockDAG architecture.  
Kaspa is a high-performance, proof-of-work blockchain built on a BlockDAG consensus model.  
Learn more: [https://kaspa.org](https://kaspa.org)

## License

This project is licensed under the MIT License.  
Feel free to use, modify, and share it.

Created for educational and experimental use.
