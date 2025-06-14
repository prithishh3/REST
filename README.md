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

If you use **REST** in your research, please cite the following paper:

> Halder, P., Mukai, T., & Das, H. S. (2023). *Modeling Heterogeneous Dust Particles: An Application to Cometary Polarization*. The Astrophysical Journal, 946(1), 69. https://doi.org/10.3847/1538-4357/acbf52

### BibTeX:
```bibtex
@article{Halder2023REST,
  author = {Halder, Prithish and Mukai, Toshinori and Das, Himadri Sekhar},
  title = {Modeling Heterogeneous Dust Particles: An Application to Cometary Polarization},
  journal = {The Astrophysical Journal},
  volume = {946},
  number = {1},
  pages = {69},
  year = {2023},
  doi = {10.3847/1538-4357/acbf52},
  url = {https://iopscience.iop.org/article/10.3847/1538-4357/acbf52}
}


