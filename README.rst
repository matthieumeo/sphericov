Instructions
############

This repository hosts the companion Jupyter notebook for the paper "Nonparametric Estimation of Covariance and Autocovariance Operators on the Sphere", from Alessia Caponera, Julien Fageot, Matthieu Simeoni and Victor Panaretos.

The code was written by `Matthieu Simeoni <mailto:matthieu.simeoni@gmail.com>`_. 

Scope
=====

This Jupyter notebook allows to reproduce the simulations, numerical experiments and plots of Section 6 of the paper. 
   
Installation
============

The notebook requires Python 3.9 or greater. It is developed and tested on x86_64 systems running MacOS and Linux.


Dependencies
------------

The notebook extra dependencies are listed in the file ``requirements.txt``.
It is recommended to install those extra dependencies in an Anaconda environment `Miniconda <https://conda.io/miniconda.html>`_ or
`Anaconda <https://www.anaconda.com/download/#linux>`_. 

.. code-block:: bash

   >> conda create -n sphericov python=3.9
   >> conda activate sphericov
   >> pip install -r requirements.txt

Run the code
------------

Once the dependencies installed, you can run the companion notebook by executing the following commands: 

.. code-block:: bash

   >> git clone https://github.com/matthieumeo/sphericov
   >> cd <repository_dir>/
   >> conda activate sphericov
   >> jupyter lab companion_nb.ipynb

