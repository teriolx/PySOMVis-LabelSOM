# LabelSOM

This repository is a fork of the implementation of the PySOMVis framework, a tool for visualizing SOMs. We implement an additional type of visualization - the LabelSOM. The implementation is contained within a new `LabelSOM` class, which is implemented in the [coding_assignment](PySOMVis/coding_assignment.ipynb) jupyter notebook. For a demonstration of the use, please refer directly to the class documentation in the notebook.

Additionally, refer to the following directories:
- [figures](PySOMVis/figures/) - to see the figures created by `LabelSOM`
- [provenance_info](PySOMVis/provenance_info) - to see the associated provenance information files for the artifacts created during the experiments including figures, model weights, and visualizations
- [trained_weights](PySOMVis/trained_weights/) - to access the weight matrices that resulted from our training of the SOM

**Authors:** Johannes Le and Terezia Olsiakova

**Citation for the original PySOMVis tool:**

<sub>1. Sergei Mnishko and Andreas Rauber. Som visualization framework in python, including somstreamvis, a time series visualization. In Jan Faigl, Madalina Olteanu, and Jan Drchal, editors, Advances in Self-Organizing Maps, Learning Vector Quantization, Clustering and Data Visualization, pages 98–107, Cham, 2022. Springer International Publishing. DOI: https://doi.org/10.1007/978-3-031-15444-7_10</sub>
