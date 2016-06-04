sac-civic-hack-2016
-------------------

Python-based [Jupyter notebook](http://jupyter.org/) for visualizing Sacramento's _Promise Zone_ data.  Maps are generated with [Folium](https://github.com/python-visualization/folium), a Python wrapper for [Leaflet](http://leafletjs.com/).  Map data comes from Code4Sac's [ndoch-2016](https://github.com/code4sac/ndoch-2016).

Setup
=====

These steps are geared towards a Mac.  There are _probably_ similar Windows step...I dunno.

1. Install Python 3 (if you don't already have it).

        brew install python3

1. Create Python virtual environment for this project.

        pyvenv ~/venv/sac-civic-hack-2016

    **Note:** This is not required, but will keep this project's dependecies isolated.

1. Enable `sac-civic-hack-2016` virtual environment.

        source ~/venv/sac-civic-hack-2016/bin/activate

1. Install dependencies.

        pip install -r requirements.txt

1. Run notebook.

        jupyter notebook

