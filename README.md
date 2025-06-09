# BlockDAG Visualizer

> **⚠️ DISCLAIMER:** This is a **purely interactive simulation** and **not** a real BlockDAG. It does **not** connect to Kaspa’s mainnet or any live blockchain.  
> Its purpose is educational/experimental only.

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
2. Go to **Settings → Pages**.  
3. Select the `main` branch and the `/root` folder (or `/docs` if applicable).  
4. Click **Save**.

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

- **Target BPS** – adjust how many blocks are generated per second.  
- **Zoom Controls** – zoom in/out using the HUD buttons or mouse wheel.  
- **HUD Toggles** – show/hide block labels and connection lines.  
- **Reset** – clears the graph and resets the simulation.

## File Structure

```
blockdag-visualizer/
├── index.html       # Main HTML file (contains all JS/CSS in one)
├── README.md        # This file
```

## Credits

This project is *inspired* by Kaspa’s BlockDAG architecture but is strictly a visualization/simulation.  
Kaspa is a high-performance, proof-of-work blockchain built on a BlockDAG consensus model.  
Learn more: [https://kaspa.org](https://kaspa.org)

## Donation

If you find this project useful and would like to support continued development, consider donating Kaspa 🟢

**Kaspa Address:**  
`kaspa:qpvexnc0mj8tty8papgwgcy9n5n3wnqxgd3jslhggfzh4xjtxv2rvrfarzd5v`

Click the <img src="assets/kaspa-icon-32x32.png" alt="Kaspa" height="20" style="vertical-align:middle;"> **Donate KASPA** button in the app to copy this address to your clipboard instantly.



## License

This project is licensed under the MIT License.  
Feel free to use, modify, and share it.

---

**Created for educational and experimental use only.**
