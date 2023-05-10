.. container:: cell markdown
   :name: f1fa8a3e

   .. rubric:: Installation
      :name: installation

.. container:: cell markdown
   :name: d1ad3eee

   The SpatialGlue package has been developed based on the pytorch
   framework and can be implemented with both GPU and CPU. Using GPU
   acceleration can significantly speed up the integration progress. So
   we recommend running the package with GPU first.

   To ensure smooth installation and execution of the package, it's
   important to have PyTorch and CUDA (including CUDNN) installed
   correctly. These dependencies are necessary for GPU acceleration.
   Make sure you have the appropriate GPU drivers installed on your
   system as well.

   To run the SpatialGlue package, two methods are provided. Note that
   the installation of all packages included in file 'requirement.txt'
   are needed.

.. container:: cell markdown
   :name: 098ef3c7

   .. rubric:: 1. Installation from PyPI (Python Package Index):
      :name: 1-installation-from-pypi-python-package-index

.. container:: cell markdown
   :name: 10c4aeb6

   -  Open a terminal or command prompt.

   -  Run the following command: '**pip install SpatialGlue**'

   -  This command will download and install the SpatialGlue package
      from PyPI along with its dependencies. If any of the dependencies
      listed in the 'requirement.txt' file are missing, they will be
      installed automatically.

      Note: please ensure the pip version is python3.

.. container:: cell markdown
   :name: 7e42d2c8

   .. rubric:: 2. Anaconda
      :name: 2-anaconda

.. container:: cell markdown
   :name: 1a52aa6f

   For convenience, we recommend using a separate conda environment for
   running SpatialGlue. Please make ensure annaconda3 is installed on
   your system. If you haven't installed it yet, you can download and
   install Anaconda3 from the official Anaconda website
   (https://www.anaconda.com/products/individual).

   #. Create conda environment and install SpatialGlue package.

.. container:: cell markdown
   :name: c236a088

   -  Create an environment called SpatialGlue

      **conda create -n SpatialGlue python=3.8**

   -  Activate your environment

      **conda activate SpatialGlue**

   -  Install SpatialGlue package

      **pip install SpatialGlue**

.. container:: cell markdown
   :name: 5f9a2ad0

   #. To use the environment in jupyter notebook, add python kernel for
      this environment.

      **pip install ipykernel**

      **python -m ipykernel install --user --name=SpatialGlue**
