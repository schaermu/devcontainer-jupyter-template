# A Dev Container template for Jupyter Notebooks
If you prefer developing jupyter notebooks with Visual Studio Code instead of the native Jupyter Notebooks interface, this is for you. It runs a python3 container (with an ipython kernel installed) with the most common libraries like pandas, matplotlib, scikit-learn or tensorflow.

# Usage
Simply have the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed in Visual Studio Code and open the repository. Everything else will be prompted VS Code.

# A note on GPU usage
If you plan to leverage your GPU for training, make sure you have the [NVIDIA Container Toolkit](https://github.com/NVIDIA/nvidia-docker/blob/master/README.md#quickstart) installed and you remove the comment in front of `"runArgs": ["--gpus", "all"]`.