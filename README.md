# Explainable AI for Earth Science: Practical Concepts, Workflows, and Pitfalls

*ELLIS Summer School: AI for Earth and Climate Sciences*  
*Jena, Germany — September 1–5, 2025*


## Overview
Hands-on materials for the XAI session.  
We will explore how attribution methods, in particular **Integrated Gradients (IG)**, can be applied to time-series models in Earth science.

Reference:
Jiang, S., Sweet, L.-b., Blougouras, G., Brenning, A., Li, W., Reichstein, M., et al. (2024). How interpretable machine learning can benefit process understanding in the geosciences. Earth's Future, 12, e2024EF004540. https://doi.org/10.1029/2024EF004540

## Getting Started
Clone the repository:

```bash
git clone https://github.com/ELLIS-Jena-Summer-School/XAI-tutorial.git
cd XAI-tutorial
```

Create the environment from the provided file:

```bash
conda env create -f environment.yml
conda activate xai
```

Then launch the notebook:
```bash
jupyter notebook
```

Open `xai_tutorial.ipynb` and follow the instructions.
