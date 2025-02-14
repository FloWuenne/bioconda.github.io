:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-harmony'
.. highlight: bash

r-harmony
=========

.. conda:recipe:: r-harmony
   :replaces_section_title:
   :noindex:

   Fast\, sensitive and accurate integration of single\-cell data with Harmony

   :homepage: https://github.com/immunogenomics/harmony
   :license: GPL-3.0-only
   :recipe: /`r-harmony <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-harmony>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-harmony/meta.yaml>`_

   


.. conda:package:: r-harmony

   |downloads_r-harmony| |docker_r-harmony|

   :versions:
      
      

      ``0.1-6``,  ``0.1-5``,  ``0.1-4``,  ``0.1-3``,  ``0.1-2``,  ``0.1-1``,  ``0.1-0``

      

   
   :depends bioconductor-singlecellexperiment: 
   :depends libgcc-ng: ``>=12``
   :depends libstdcxx-ng: ``>=12``
   :depends r-base: ``>=4.3,<4.4.0a0``
   :depends r-cowplot: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-irlba: 
   :depends r-matrix: 
   :depends r-rcpparmadillo: 
   :depends r-rcppprogress: 
   :depends r-rlang: 
   :depends r-tibble: 
   :depends r-tidyr: 
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

      mamba install r-harmony

   and update with::

      mamba update r-harmony

  To create a new environment, run::

      mamba create --name myenvname r-harmony

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/r-harmony:<tag>

   (see `r-harmony/tags`_ for valid values for ``<tag>``)


.. |downloads_r-harmony| image:: https://img.shields.io/conda/dn/bioconda/r-harmony.svg?style=flat
   :target: https://anaconda.org/bioconda/r-harmony
   :alt:   (downloads)
.. |docker_r-harmony| image:: https://quay.io/repository/biocontainers/r-harmony/status
   :target: https://quay.io/repository/biocontainers/r-harmony
.. _`r-harmony/tags`: https://quay.io/repository/biocontainers/r-harmony?tab=tags


.. raw:: html

    <script>
        var package = "r-harmony";
        var versions = ["0.1","0.1","0.1","0.1","0.1"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-harmony/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-harmony/README.html