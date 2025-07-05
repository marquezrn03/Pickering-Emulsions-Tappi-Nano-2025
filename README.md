# Interactive nanocellulose-stabilized Pickering emulsion data explorer

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15808694.svg)](https://doi.org/10.5281/zenodo.15808694)

This repository contains the source code and curated dataset for the "Interactive nanocellulose-stabilized Pickering emulsion data explorer," a web-based tool designed to help researchers visualize and explore the scientific literature in the field of nanocellulose-stabilized emulsions.

This work was developed by Ronald Marquez, Roberto J. Aguado, Blaise Tardy, and Marc Delgado Aguilar, and was presented at the **Tappi Nano 2025 conference in Girona, Spain**.

---

## 📖 Project overview

Pickering emulsions stabilized by nanocellulose are a rapidly growing field of research. However, understanding the complex relationships between nanocellulose properties, processing conditions, and emulsion outcomes requires analyzing a vast body of literature. This tool aims to simplify that process.

It provides an interactive interface to a database manually curated from over 80 peer-reviewed articles. Researchers, students, and industry professionals can use this platform to:
* Identify trends and correlations in the existing data.
* Discover knowledge gaps for future research.
* Accelerate the design and development of new emulsion-based applications.

![Screenshot of the Data Explorer](https://i.imgur.com/zKVBN0r.png)

## Key features

* **Interactive scatter plot:** Dynamically explore the relationship between any two numerical variables from the dataset. Data points can be colored by category (e.g., nanocellulose type) and filtered to isolate subsets of interest.
* **Droplet size distribution analysis:** Compare emulsion droplet sizes across different categorical groups using box plots.
* **Correlation matrix:** A heatmap that visualizes the Pearson correlation coefficients between all numerical parameters in the database.
* **Direct article linking:** Click on any data point in the scatter plot to open the original scientific article via its DOI.
* **CSV Data download:** The complete, curated dataset is available for download as a CSV file directly from the user interface.

## 🛠️ Technology stack

* **Frontend:** HTML5, Tailwind CSS
* **Data Visualization:** Plotly.js
* **Logic:** Vanilla JavaScript

## How to use

### Online (Recommended)
The easiest way to use the tool is to visit the live demo link: [https://marquezrn03.github.io/Pickering-Emulsions-Tappi-Nano-2025/](https://marquezrn03.github.io/Pickering-Emulsions-Tappi-Nano-2025/)

## The Dataset

The dataset was manually curated from over 80 scientific articles and is embedded as a JSON object within the `index.html` file. It includes parameters such as:
* Nanocellulose type (CNC, CNF, etc.) and source (wood, cotton, bacterial, etc.)
* Chemical modifications and surface properties
* Particle dimensions and aspect ratio
* Emulsion type (o/w, w/o), oil type, and concentration
* Resulting droplet size and stability

The data itself is licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. You are free to share and adapt the data for any purpose, provided you give appropriate credit.

## ✍️ How to Cite

If you use this software or its dataset in your research, please cite it. This ensures that the work is properly credited and helps others find the tool.

#### Citing the Software/Tool:

#### BibTeX Entry:
```bibtex
@software{marquez_2025_nanocellulose,
  author       = {Marquez, Ronald and
                  Aguado, Roberto J. and
                  Tardy, Blaise and
                  Delgado Aguilar, Marc},
  title        = {{Nanocellulose Emulsion Data Explorer: An 
                   Interactive Visualization Tool for Scientific
                   Literature}},
  month        = jul,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.15808695},
  url          = {[https://doi.org/10.5281/zenodo.15808695](https://doi.org/10.5281/zenodo.15808695)}
}

📜 License
The source code of this project is licensed under the MIT License. See the LICENSE file for more details.
