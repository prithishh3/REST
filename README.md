# REST: Rough Ellipsoid Structure Tools

**REST** (Rough Ellipsoid Structure Tools) is a Java-based GUI application for generating physically realistic dust aggregate structures used in astrophysical light scattering studies.

---

## 🌐 About

REST helps create ellipsoids, super-ellipsoids, and aggregate particle structures that resemble real cosmic dust grains, suitable for DDSCAT's `CALLTARGET` input format. Structures include:

- Strongly Damaged Sphere (SDS)
- Rough Surface (RS)
- Poked Structure (PS)
- Rough Surface Super-Ellipsoid (RS-SE)
- Poked Structure Super-Ellipsoid (PS-SE)
- Rough Fractal Aggregates (RFA)

---

## 💻 Platform Support

| Platform | Supported | Notes                  |
|----------|-----------|------------------------|
| Windows  | ✅        | Windows `.bat` provided |
| Linux    | ✅        | Will be available soon  |
| macOS    | ✅        | Will be available soon  |

---

## 🚀 Getting Started (Windows)

1. Download the latest `REST_0.1.1_Windows.zip` from [Releases](https://github.com/yourusername/REST/releases).
2. Extract the folder.
3. Double-click `REST.bat` inside the REST directory to launch the GUI.

> Ensure you have Java 11 (or later) installed.

---

## ⚙️ Requirements (Windows)

### For Linux/macOS users:
- Java 11
- `gfortran`
- Python 3
- PyVista (`pip install pyvista`)
- VTK (`pip install vtk`)

To launch (Windows):

Doble click the `REST.bat` file inside the REST directory.

## 📚 Citation

If you use **REST** in your research, please cite the following publication:

> Halder, P. (2022). *REST: A Java Package for Crafting Realistic Cosmic Dust Particles*. The Astrophysical Journal Supplement Series, 263(1), 3. https://doi.org/10.3847/1538-4365/ac9183

### BibTeX:
```bibtex
@article{Halder_2022,
  doi = {10.3847/1538-4365/ac9183},
  url = {https://dx.doi.org/10.3847/1538-4365/ac9183},
  year = {2022},
  month = {oct},
  publisher = {The American Astronomical Society},
  volume = {263},
  number = {1},
  pages = {3},
  author = {Halder, Prithish},
  title = {REST: A Java Package for Crafting Realistic Cosmic Dust Particles},
  journal = {The Astrophysical Journal Supplement Series},
  abstract = {The overall understanding of cosmic dust particles is mainly inferred from the different Earth-based measurements of interplanetary dust particles and space missions such as Giotto, Stardust, and Rosetta. The results from these measurements indicate the presence of a wide variety of morphologically significant dust particles. To interpret the light-scattering and thermal emission observations arising due to dust in different regions of space, it is necessary to generate computer-modeled realistic dust structures of various shapes, sizes, porosity, bulk density, aspect ratio, and material inhomogeneity. The present work introduces a Java package called Rough Ellipsoid Structure Tool (REST), which is a collection of multiple algorithms, that aims to craft realistic rough-surface cosmic dust particles from spheres, superellipsoids, and fractal aggregates depending on the measured bulk density and porosity. Initially, spheres having N  d  dipoles or lattice points are crafted by selecting random material and space seed cells to generate a strongly damaged structure, rough surface, and poked structure. Similarly, REST generates rough-surface superellipsoids and poked structure superellipsoids from initial superellipsoid structures. REST also generates rough fractal aggregates, which are fractal aggregates having rough-surface irregular grains. REST has been applied to create agglomerated debris, agglomerated debris superellipsoids, and mixed-morphology particles. Finally, the light-scattering properties of the respective applied structures are studied to ensure their applicability. REST is a flexible structure tool that shall be useful for generating various types of dust structures that can be applied to studying the physical properties of dust in different regions of space.}
}



