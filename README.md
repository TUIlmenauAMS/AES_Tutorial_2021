# AES Toturial 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TUIlmenauAMS/AES_Tutorial_2021/HEAD)

Easiest way to run locally:
- Install Conda or Miniconda: https://docs.conda.io/en/latest/miniconda.html / https://docs.anaconda.com/anaconda/install/index.html
- Create an dnevironm from a .yml file (located in the binder folder) : https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file
- Activate your newly created environment: https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment

Voilá, everything should be configured and you can lauch the jupuyter notebook.

Some useful jupyter commands:

 - jupyter contrib nbextension install --user (in case the nbextensions config wasn't installed properly)
 - jupyter nbextension enable --py widgetsnbextension (to enable the widgetsnbextension)
 - jupyter nbextension enable python-markdown/main (to enable markdown extension)
 - jupyter trust *.ipynb (to make all notebooks trusted)
 - jupyter nbextension enable hide_input/main (to enable hide_input extension)
