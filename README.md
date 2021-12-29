# jaeger-intro

This repository contains tutorials for using [Jupyter](https://jupyter.org/) notebooks with
[Jaeger](https://www.jaegertracing.io/).

## Pre-requisites

For the static example, you don't need Jaeger.  We will begin by looking at
data captured from Jaeger.

If you don't have Python3 and Jupyter you'll need them.

Install Jupyter using `pip install jupyterlab`

Install the data science and visualization libraries.

```Bash
pip install pandas
pip install holoviews
pip install plotly
pip install networkx
```

Run `jupyter-lab` in this repo directory (or any directory above it.)
Navigate to any _.ipynb_ file and open it.

## Notebooks

To learn this system, start here

- [Static](static.ipynb) A static file with pre-captured data.  Render it using HoloViews.
- [Real](real.ipynb) Real queries against a Jaeger server, rendered with Holoviews.
- [Jaeger Community Demo](august-demo.ipynb) The demo I gave on the Jaeger community call, 11-November 2021
