{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "f1fa8a3e",
   "metadata": {},
   "source": [
    "# Installation"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "d1ad3eee",
   "metadata": {},
   "source": [
    "The SpatialGlue package has been developed based on the pytorch framework and can be implemented with both GPU and CPU. Using GPU acceleration can significantly speed up the integration progress. So we recommend running the package with GPU first. \n",
    "\n",
    "To ensure smooth installation and execution of the package, it's important to have PyTorch and CUDA (including CUDNN) installed correctly. These dependencies are necessary for GPU acceleration. Make sure you have the appropriate GPU drivers installed on your system as well.\n",
    "\n",
    "To run the SpatialGlue package, two methods are provided. Note that the installation of all packages included in file 'requirement.txt' are needed. "
   ]
  },
  {
   "cell_type": "markdown",
   "id": "098ef3c7",
   "metadata": {},
   "source": [
    "# 1. Installation from PyPI (Python Package Index):"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "10c4aeb6",
   "metadata": {},
   "source": [
    "* Open a terminal or command prompt.\n",
    "* Run the following command: '**pip install SpatialGlue**'\n",
    "* This command will download and install the SpatialGlue package from PyPI along with its dependencies. If any of the dependencies listed in the 'requirement.txt' file are missing, they will be installed automatically.\n",
    "\n",
    "  Note: please ensure the pip version is python3."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7e42d2c8",
   "metadata": {},
   "source": [
    "# 2. Anaconda"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "1a52aa6f",
   "metadata": {},
   "source": [
    "For convenience, we recommend using a separate conda environment for running SpatialGlue. Please make ensure annaconda3 is installed on your system. If you haven't installed it yet, you can download and install Anaconda3 from the official Anaconda website (https://www.anaconda.com/products/individual).\n",
    "\n",
    "1. Create conda environment and install SpatialGlue package."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "c236a088",
   "metadata": {},
   "source": [
    "* Create an environment called SpatialGlue\n",
    "\n",
    "  **conda create -n SpatialGlue python=3.8** \n",
    "  \n",
    "\n",
    "* Activate your environment\n",
    "\n",
    "  **conda activate SpatialGlue**\n",
    "  \n",
    "\n",
    "* Install SpatialGlue package\n",
    "\n",
    "  **pip install SpatialGlue**"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5f9a2ad0",
   "metadata": {},
   "source": [
    "2. To use the environment in jupyter notebook, add python kernel for this environment.\n",
    "\n",
    "   **pip install ipykernel**\n",
    "\n",
    "   **python -m ipykernel install --user --name=SpatialGlue**"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "long",
   "language": "python",
   "name": "long"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.0"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
