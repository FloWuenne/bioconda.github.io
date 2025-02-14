:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'pybbi'
.. highlight: bash

pybbi
=====

.. conda:recipe:: pybbi
   :replaces_section_title:
   :noindex:

   Python bindings to UCSC Big Binary \(bigWig\/bigBed\) file library

   :homepage: https://github.com/nvictus/pybbi
   :license: MIT / MIT
   :recipe: /`pybbi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pybbi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pybbi/meta.yaml>`_

   


.. conda:package:: pybbi

   |downloads_pybbi| |docker_pybbi|

   :versions:
      
      

      ``0.3.6-0``,  ``0.3.5-0``,  ``0.3.2-2``,  ``0.3.2-1``,  ``0.3.2-0``,  ``0.3.0-1``,  ``0.3.0-0``

      

   
   :depends libgcc-ng: ``>=12``
   :depends libpng: ``>=1.6.39,<1.7.0a0``
   :depends libzlib: ``>=1.2.13,<1.3.0a0``
   :depends numpy: ``>=1.21.6,<2.0a0``
   :depends openssl: ``>=3.2.0,<4.0a0``
   :depends python: ``>=3.10,<3.11.0a0``
   :depends python_abi: ``3.10.* *_cp310``
   :depends six: 
   :requirements:

   .. rubric:: Installation

  You need a conda-compatible package manager
  (currently either `micromamba <https://mamba.readthedocs.io>`_, `mamba <https://mamba.readthedocs.io>`_, or `conda <https://docs.conda.io/projects/conda>`_)
  and the Bioconda channel already activated (see :ref:`set-up-channels`).

  While any of above package managers is fine, it is currently recommended to use either
  micromamba or mamba (see `here <https://mamba.readthedocs.io>`_ for installation instructions).
  We will show all commands using mamba below, but the arguments are the same for the two
  others.

  Given that you already have a conda environment in which you want to have this package, install with::

      mamba install pybbi

   and update with::

      mamba update pybbi

  To create a new environment, run::

      mamba create --name myenvname pybbi

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/pybbi:<tag>

   (see `pybbi/tags`_ for valid values for ``<tag>``)


.. |downloads_pybbi| image:: https://img.shields.io/conda/dn/bioconda/pybbi.svg?style=flat
   :target: https://anaconda.org/bioconda/pybbi
   :alt:   (downloads)
.. |docker_pybbi| image:: https://quay.io/repository/biocontainers/pybbi/status
   :target: https://quay.io/repository/biocontainers/pybbi
.. _`pybbi/tags`: https://quay.io/repository/biocontainers/pybbi?tab=tags


.. raw:: html

    <script>
        var package = "pybbi";
        var versions = ["0.3.6","0.3.5","0.3.2","0.3.2","0.3.2"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pybbi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/pybbi/README.html