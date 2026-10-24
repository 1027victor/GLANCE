Installation
============

We recommend using a dedicated Python 3.10 environment:

.. code-block:: shell

   conda create -n glancevae python=3.10.19 -y
   conda activate glancevae

**GPU support.** If you plan to use GPU acceleration, install the appropriate
CUDA-enabled version of `PyTorch <https://pytorch.org/get-started/locally/>`_
before installing GLANCE. For example, for CUDA 12.6:

.. code-block:: shell

   pip install torch==2.8.0 --index-url https://download.pytorch.org/whl/cu126

**Install GLANCE.** Install GLANCE directly from GitHub:

.. code-block:: shell

   pip install "glancevae @ git+https://github.com/yilitai/GLANCE.git"

To install the additional dependencies used in the tutorial notebooks:

.. code-block:: shell

   pip install "glancevae[tutorials] @ git+https://github.com/yilitai/GLANCE.git"

These commands require Git to be installed.
