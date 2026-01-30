# csc-51074-notes
My personal notes for CSC-51074: Digital Representations and Analysis of Shapes (École Polytechnique).

## Schedule
### 1. Introduction & Fundamentals
- Transformations
- Rotations
- Homogeneous coordinates
- Projective geometry

#### References
- [Meshless animation of fracturing solids (Pauly et al. 1998)]https://dl.acm.org/doi/10.1145/1073204.1073296

### 2. Transformations & Rotations
- Euclidean, affine, and projective geometry.
- Isometries: rotations + translations.
- Rotation representations:
    - Matrices
    - Euler angles (and gimbal lock)
    - Quaternions
- Homogeneous coordinates:
    - Linearizing translations
    - Projections (orthographic & perspective)

### 3. Curves Galore
- Differential geometry of curves:
    - Arc-length
    - Curvature
    - Frenet–Serret frames
- Curve representations:
    - Explicit, parametric, implicit
- Interpolation & approximation:
    - Linear interpolation
    - Polynomial (Lagrange) interpolation
    - Splines (cubic splines)
- Subdivision curves:
    - Chaikin
    - Bézier
    - B-splines

### 4. Surfaces, Point Clouds & Implicits
- Differential geometry of surfaces:
    - Normals
    - Principal curvatures
    - Mean & Gaussian curvature
- Point clouds:
    - Acquisition
    - Noise & outliers
    - Normal estimation (PCA)
- Registration:
    - ICP
    - Procrustes / Kabsch
- Implicit surfaces:
    - Level sets
    - Marching Cubes
    - Dual Contouring

### 5. Polygonal Meshes
- Meshes as topological + geometric objects.
- Simplicial complexes.
- Manifoldness & boundaries.
- Discrete differential geometry:
    - Angle deficit curvature
- Mesh data structures:
    - Half-edge
    - Triangle-based
- Mesh processing:
    - Denoising (Laplacian smoothing)
    - Simplification (edge contraction, QEM)

### 6. Surface Reconstruction
- From point clouds to meshes
- Computational geometry methods:
    - Alpha shapes
    - Crust, Power Crust
    - Voronoi / Delaunay
- Implicit reconstruction:
    - Indicator functions
    - Poisson reconstruction
- Robust variants:
    - Unsigned distance + sign inference
    - Voronoi-based eigen reconstruction

### 7. Geometry Processing I
- Mesh parameterization:
    - Fixed vs free boundary
    - Harmonic maps
    - Conformal maps (LSCM, DCP)
    - Spectral parameterization
- Applications:
    - Texture mapping
    - Normal mapping
    - Remeshing
    - Compression
- Geodesic distances:
    - Fast marching
    - Heat method

### 8. Subdivision & Eigenanalysis
- Subdivision curves:
    - Chaikin
    - Cubic B-splines
- Subdivision surfaces:
    - Doo–Sabin
    - Catmull–Clark
    - Loop
- Eigenanalysis:
    - Graph Laplacians
    - Laplace–Beltrami operator
- Spectral methods:
    - Clustering
    - Shape DNA
    - Heat Kernel Signature

#### Related Material
- [Spectral mesh processing (Lévy et al. 2010)](https://dl.acm.org/doi/10.1145/1837101.1837109)
- [Eigenanalysis in Computer Graphics](https://dl.acm.org/doi/10.1145/3721241.3733993)

### 9. Geometry Processing II
- Mesh deformation:
    - Cage-based editing (MVC, harmonic coords)
    - Laplacian & Poisson editing
    - ARAP
- Vector field processing:
    - Triangle-based fields
    - Edge-based (DEC)
    - Vertex-based (parallel transport)
- Holonomy, connections, curvature
- Design & grooming applications

### 10. Data-Driven Geometric Modeling
- Feature-based shape comparison:
    - HKS
    - Bag-of-Words
- 3D deep learning paradigms:
    - Multi-view
    - Volumetric
    - Point-based
    - Surface-based
    - Implicit neural fields
- Landmark models:
    - PointNet
    - Point Transformers
    - DeepSDF
    - NeRF

## Books
- [Polygon Mesh Processing](https://www.pmp-book.org)
- Differential Geometry of Curves and Surfaces
- [Geometric Deep Learning](https://geometricdeeplearning.com)

## Other Courses
- [CSC-2520: Geometry Processing (University of Toronto)](https://github.com/alecjacobson/geometry-processing-csc2520)
- [Discrete Differential Geometry (Keenan Crane)](https://www.cs.cmu.edu/~kmcrane/Projects/DDG/), [Website](https://brickisland.net/ddg-web), [Notes](https://www.cs.cmu.edu/~kmcrane/Projects/DDG/paper.pdf), [Lectures](https://www.youtube.com/playlist?list=PL9_jI1bdZmz0hIrNCMQW1YmZysAiIYSSS), [Exercises](https://github.com/GeometryCollective/ddg-exercises)

## Libraries
- libigl
- CGAL
- Polyscope

## Miscellaneous
