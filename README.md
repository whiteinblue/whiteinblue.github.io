<h1 align="center">EarthCrafter: Scalable 3D Earth Generation via Dual-Sparse Latent Diffusion</h1>

### Abstract
<span style="font-size: 12px; font-weight: 700;">
Despite the remarkable developments achieved by recent 3D generation works, scaling these methods to geographic extents, such as modeling thousands of square kilometers of Earth’s surface, remains an open challenge.
We address this through a dual innovation in data infrastructure and model architecture.
First, we introduce Aerial-Earth3D, the largest 3D aerial dataset to date, consisting of 50k curated scenes (each measuring 600m$\times$600m) captured across the U.S. mainland, comprising 45M multi-view Google Earth frames.
Each scene provides pose-annotated multi-view images, depth maps, normals, semantic segmentation, and camera poses, with explicit quality control to ensure terrain diversity.
Building on this foundation, we propose EarthCrafter, a tailored framework for large-scale 3D Earth generation via sparse-decoupled latent diffusion. Our architecture separates structural and textural generation:
1) Dual sparse 3D-VAEs compress high-resolution geometric voxels and textural 2D Gaussian Splats (2DGS) into compact latent spaces, largely alleviating the costly computation suffering from vast geographic scales while preserving critical information. 
2) We propose condition-aware flow matching models trained on mixed inputs (semantics, images, or neither) to flexibly model latent geometry and texture features independently.
Extensive experiments demonstrate that EarthCrafter performs substantially better in extremely large-scale generation.
The framework further supports versatile applications, from semantic-guided urban layout generation to unconditional terrain synthesis, while maintaining geographic plausibility through our rich data priors from Aerial-Earth3D.

### TODO List
- Inferencing and Training codes
- Data overall preparation pipeline
- Training data release (If it complies with our company regulations)
