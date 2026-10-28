### Abdullah Saad

Geospatial engineer working on **semantic 3D city models, digital twins, and generative deep learning for 3D urban data**. M.Sc. Information Technology for the Built Environment, TU Munich (thesis grade 1.0). Based in Munich.

**What I work on**

- **Generative 3D:** conditional 3D diffusion models (3D U-Net, DDPM/DDIM) that generate semantically enriched buildings from CityGML
- **Geospatial data pipelines:** CityGML 2.0/3.0, IFC, point clouds, voxelisation, PostGIS, GPU-accelerated batch processing
- **Reality capture & digital twins:** 3D data operations for industrial digital twins at NavVis

**Selected projects**

| Project | What it does |
|---|---|
| [Urban-Auto-Vox](https://github.com/tum-gis/Urban-Auto-Vox) | Dockerized, CUDA-accelerated pipeline turning CityGML buildings into semantically labelled voxel grids in PostGIS (TUM Chair of Geoinformatics) |
| [urban-auto-vox-rs](https://github.com/Atsaad/urban-auto-vox-rs) | Rust implementation of the pipeline: CityGML → OBJ → CUDA voxelisation → CSV/PostGIS in one `docker compose up` |
| [voxel-viewer](https://github.com/Atsaad/voxel-viewer) | Converts voxel CSV/binvox to coloured OBJ, PLY and glTF with automatic per-class colouring; CLI + GUI, 77 tests |
| [voxel-roof-study](https://github.com/Atsaad/voxel-roof-study) | Blind perceptual study comparing real and generated 3D buildings, part of my M.Sc. thesis |

**Tools:** Python · PyTorch · Rust · SQL/PostGIS · Docker · CUDA · CityGML · IFC · FME · QGIS

[LinkedIn](https://www.linkedin.com/in/atsaad/) · atsaad89@gmail.com
