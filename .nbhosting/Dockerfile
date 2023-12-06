# --------
FROM nbhosting/minimal-notebook

RUN true \
 && pip install numpy pandas matplotlib chart_studio bokeh jupyter-bokeh k3d autograd \
 && pip install requests pytest \
 && pip install nbautoeval ipythontutor \
 && pip install jupyter jupytext jupyterlab-myst \
 && pip install jupyterlab-courselevels ipywidgets ipympl jupyterlab-rise \
 && apt-get install -y graphviz && pip install graphviz \
 && pip install pylint \
 && pip install aiohttp \
 && true
