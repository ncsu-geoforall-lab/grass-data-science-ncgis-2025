# Geospatial Data Science with GRASS (NC GIS 2025)

This is a set of Jupyter Notebooks for workshop at NC GIS 2025 conference.

Presenters: Vaclav (Vashek) Petras, Corey White

## How to run the notebooks

The workshop can be run online in [MyBinder](https://mybinder.org/) and [Google Colab](https://colab.research.google.com). This is a convenient way, since no installation is needed.

### MyBinder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ncsu-geoforall-lab/grass-data-science-ncgis-2025/HEAD?urlpath=%2Fdoc%2Ftree%2Fworkshop_part_1_intro.ipynb)

To run the notebook in MyBinder, click the launch button above.

The software and dataset is downloaded and installed into the environment.
Other notebooks and files can be accessed through the JupyterLab interface
on the left.

### Google Colab

<a target="_blank" href="https://colab.research.google.com/github/ncsu-geoforall-lab/grass-data-science-ncgis-2025/blob/main/colab_notebook.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

To run the notebook in Google Colab, click the open button above.

In Google Colab, we don't have pre-installed the software needed, so go ahead and execute the first cell to install it. Also, in order to avoid the need to repeat the installation, we merged all notebooks into one long notebook.

### Local Setup

Please, don't do a local setup for this short workshop so that we can focus on analysis.
However, if you want to explore local setup, it might be advantageous to explore the
[notebooks for Windows and macOS here](https://github.com/ncsu-geoforall-lab/GIS714-assignments/tree/main/GRASS_GIS_Foundations).
For Linux, the setup will be relatively straightforward even if you have to use a virtual environment.
Having GRASS on a non-standard path (which is not on system path), will require:

```python
import os
os.environ["PATH"] += ":/path/to/directory/where/grass/executable/is/"
```

## Abstract

This hands-on NCGIS 2025 pre-conference workshop introduces participants to GRASS as a powerful geospatial processing engine integrated with Python for advanced data science workflows.

Using online Jupyter notebooks, participants will explore how GRASS tools can handle large datasets, automate spatial analysis using Python, and perform complex computations.

Participants will work through examples of raster and vector processing, spatial statistics, and image classification. No previous experience with GRASS is required, but either basic Python or advanced geospatial experience is recommended.

Duration: 4 hours

## Author

Vaclav Petras, NC State University, Center for Geospatial Analytics

Corey White, NC State University, Center for Geospatial Analytics

<img src="img/ncsu_cga.png" title="Center for Geospatial Analytics at NC State" width=400>

## License

This material is dual licensed under GNU FDL 1.3 and CC BY-SA 4.0.

## Acknowledgement
This workshop was developed and delivered with the support of the U.S. National Science Foundation, award [2303651](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2303651).

<img src="img/NSF_logo.png" title="NSF" width=150>
