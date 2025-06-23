# 📘 Individual Research Project (IRP) Thesis

This repository contains the LaTeX source code for the MSc Individual Research Project (IRP) thesis at Cranfield University. The thesis explores *The modelling of a 6-DOF fixed wing UAV with PX4 Software-In-The-Loop (SITL) and Hardware-In-The-Loop (HITL)*.

## 📝 Project Title

**6dof UAV + Flight test validation + PX4**

## 📂 Repository Structure


##  License
This project is licensed under the [MIT License](LICENSE).

## 📦 Building

Compile the `MAIN.tex` file using your preferred LaTeX toolchain (e.g. `pdflatex` or `latexmk`) to produce the thesis PDF. All chapter files are included via `\input` directives in `MAIN.tex`.

- `main.tex` – top-level LaTeX file that includes all chapters
- `aer.cls` – custom class file used for formatting
- `Sections/` – folder containing the title page, abstract, chapters, and appendices
- `MyBib.bib` – bibliography database
- `fpo.eps` – example figure used in the template

## 🛠️ Building the Document

The document can be compiled with `latexmk` (recommended) or directly with `pdflatex`.

```bash
latexmk -pdf main.tex
```

Make sure the required TeX packages are installed (see below). Cleaning auxiliary files can be done with `latexmk -c`.

## 📦 Dependencies

The template relies on several LaTeX packages provided by TeX Live:

- `natbib` – citation management
- `rotating` – sideways figures/tables
- `txfonts` – text and math fonts
- `graphicx` – included via the class file

The document class `aer.cls` is bundled in this repository.

## ✍️ Author

Victor Calatayud – <v.calatayudgarcia@cranfield.ac.uk>

This repository currently has no explicit license. Please contact the author if you wish to reuse the material.


