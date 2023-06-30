# time-series

This package contains all necessary files for the course *Ocean/Atmosphere Time Series Analysis*, an introduction to data and time series analysis for graduate students in oceanography, atmospheric science, and climate.  

This material is generally taught in two separate portions, a five-day and a ten-day intensive, both with five hours a day of course time.  The first intensive covers *Part I: Fundamentals*, while the second intensive covers *Part II: Spectral and Time-Frequency Analysis*.  See the course [home page](http://www.jmlilly.net/courses.html) for a list of upcoming and past courses, or [email me](mailto:jmlilly@psi.edu) to be put on the announcement list for future courses. 

To get started, just open the file `index.html` with any web browser.

There you will find lecture notes, viewable through a web browser, as well as lab files in the form of Jupyter notebooks.  The lab files have parallel translations in Matlab, Python, and Julia.  Each lab file has both an html version for convenient reading, in braces {}, as well as an ipynb version, in brackets \[\] that can be run locally.  A line through the lab's name means this translation has not yet been completed.  For those wishing to set up Jupyter notebooks to work with Matlab, instructions can be found [here](http://www.jmlilly.net/jupyter-matlab).

The lecture notes were made using [Liminal](http://www.jmlilly.net/liminal), a theme for [Remark.js](https://remarkjs.com/), itself a Javascript package for rendering Markdown and LaTeX as Powerpoint-style presentations within a web browser.  A complete distribution of [KaTeX](https://katex.org), a minimal typesetting library for LaTeX, is also included.

Version 0.3 is a considerable update over v. 0.2 that includes a complete rewrite of all the Jupyter Notebook lab files, a translation of half of these into Julia, and an integration of the Julia lab files with [RISE](https://rise.readthedocs.io/en/stable/), the Reveal.js — Jupyter/IPython Slideshow Extension, so that each file can be viewed either as a notebook or as a presentation.

Please note that these notes are a work in progress.

### Using these course notes

You can use these notes in several ways.  First, you can simply browse the [online version](http://www.jmlilly.net/course/index.html) and download the lab files in  

### Running labs in presentation mode

To use the labs in presentation mode, you'll need to install [RISE](https://rise.readthedocs.io/en/stable/), which you can do with 

```
conda install -c conda-forge rise
```

or, if you're using [mamba](https://mamba.readthedocs.io/en/latest/) or [micromamba](https://mamba.readthedocs.io/en/latest/user_guide/micromamba.html) as your package manager, these can be substituted for `conda` in the above command. 

With RISE installed, you can choose to run a notebook in Jupyter Notebook (not in JupyterLab) as a presentation by clicking on an icon that looks like a bar graph in the Jupyter Notebook toolbar, generally the last icon the right.  These presentations will look better if you choose these settings from the Jupyter Notebook menu: (i) make sure scrolling is toggled off with Cell > All Output > Toggle Scrolling, and (ii) make sure line numbers are toggled off with View > Toggle Line Numbers.  

To create your own presentations, you should see a drop-down menu on the right-hand side of each Jupyter Notebook cell that says "Slide Type"; if you don't see this, you need to choose View > Cell Toolbar > Slideshow from the menu.  Make sure you have the file `rise.css` in the directory in which the notebook is located; this is available from `labs` directory of this course or from the [RISE GitHub respository](https://github.com/damianavila/RISE).  

For you own notebooks, you'll want to edit the Jupyter Notebook metadata to configure the RISE settings, as described [here](https://rise.readthedocs.io/en/stable/customize.html#choosing-a-theme).  This is done by choosing Edit > Edit Notebook Metadata, after which you'll want to save the file and then reload in order for the changes to take effect.  Note that the customization of themes and transitions discussed in the RISE documentation refer to the Reveal.js [themes](https://revealjs.com/themes/) and [transitions](https://revealjs.com/transitions/).



### Contact and attribution

Comments, questions, bug reports, etc. are all welcome.  Feel free to email me at [jmlilly@psi.edu](mailto:jmlilly@psi.edu), or use the [GitHub issue tracker](https://github.com/jonathanlilly/time-series/issues).


If you make use of these notes, kindly cite them as:

Lilly, J. M. (2023). Ocean/Atmosphere Time Series Analysis, v. 0.31. Zenodo. [https://doi.org/10.5281/zenodo.5977995](https://doi.org/10.5281/zenodo.5977995).
