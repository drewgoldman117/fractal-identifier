# 🌀 Fractal Identifier

This project explores whether neural networks can classify different types of fractal patterns generated in Blender.

Fractals are scale-invariant, self-similar structures found in terrain, turbulence, and finance.  
Here, I generate fractal textures using Blender’s Musgrave node (FBM, Ridged, Hybrid, Multifractal, Hetero Terrain)  
and train a PyTorch CNN to identify them.

## Project Structure
- code/   → dataset generation and training scripts
- data/   → synthetic images (not tracked in Git)
- models/ → trained models (not tracked in Git)
- docs/   → project notes and analysis

## Requirements
- Blender 4.x
- Python 3.x
- PyTorch, torchvision, pandas, pillow

## Roadmap
- [ ] Generate small fractal dataset in Blender
- [ ] Train a CNN classifier in PyTorch
- [ ] Compare with classical fractal analysis methods
- [ ] Document experiments and results
