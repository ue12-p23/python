# --------
FROM nbhosting/minimal-notebook

# NOTE
# we cannot use jupyter nbextension enable/disable
# because this is no longer available under nb7
# for the record we used to have these 2:
# && jupyter nbextension enable hide_input/main \
# && jupyter nbextension install --py k3d \
RUN true \
 && pip install numpy pandas matplotlib chart_studio bokeh k3d autograd \
 && pip install requests pytest \
 && pip install nbautoeval ipythontutor \
 && pip install jupyter jupytext jupyterlab-myst \
 && pip install jupyterlab-courselevels ipywidgets ipympl jupyterlab-rise \
 && apt-get install -y graphviz && pip install graphviz \
 && pip install pylint \
 && pip install aiohttp \
 && true
