Installation
============

Leonardo requires Python>=3.9. We highly recommend using :mod:`conda` 
virtual environment to install and operate Leonardo.

PyPI
-----

#. 1. To use Leonardo with CPU, install Leonardo from PyPI using:

.. code-block:: bash

    conda create -n leonardo python=3.9
    conda activate leonardo
    pip install leonardo_toolset

or full software including Napari plugins:

.. code-block:: bash

    # for Windows or Linux users
    pip install leonardo_toolset[napari]
    # for macOS users
    pip install leonardo_toolset`[napari]`

Leonardo has now been tested on Linux and Windows and might has issue on macOS.

#. 2. To use Leonardo with GPU:
Setup Pytorch according to your own system setting, following the official guideline: https://pytorch.org/get-started/locally/
Instaall leonardo_toolset following the instructions in option 1.



.. toggle::
   :show:

    Core components in :mod:`Leonardo` are installable separately:

    .. code-block:: bash

        # Leonardo-DeStripe
        pip install lsfm-destripe
        
        # Leonardo-Fuse
        pip install lsfm-fuse

        # Leonardo-DeStripe in Napari
        pip install lsfm_destripe_napari

        # Leonardo-Fuse in Napari
        pip install lsfm_fusion_napari

Development Version
--------------------

To work with the latest development version, install from GitHub using:

.. code-block:: bash

    pip install git+https://github.com/peng-lab/leonardo_toolset.git
