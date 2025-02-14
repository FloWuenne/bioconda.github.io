:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'peka'
.. highlight: bash

peka
====

.. conda:recipe:: peka
   :replaces_section_title:
   :noindex:

   Analysis of kmers located around locations of interest

   :homepage: https://github.com/ulelab/peka
   :license: GPL-3.0
   :recipe: /`peka <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/peka>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/peka/meta.yaml>`_

   


.. conda:package:: peka

   |downloads_peka| |docker_peka|

   :versions:
      
      

      ``1.0.0-0``,  ``0.1.6-0``,  ``0.1.5-0``,  ``0.1.4-0``,  ``0.1.2-0``

      

   
   :depends matplotlib-base: ``3.1.2``
   :depends numpy: ``1.17.4``
   :depends pandas: ``0.24.2``
   :depends plumbum: ``1.6.8``
   :depends pybedtools: ``0.8.0``
   :depends python: ``3.7``
   :depends scikit-learn: ``0.21.3``
   :depends scipy: ``1.6.2``
   :depends seaborn: ``0.9.0``
   :depends textdistance: ``4.1.3``
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

      mamba install peka

   and update with::

      mamba update peka

  To create a new environment, run::

      mamba create --name myenvname peka

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/peka:<tag>

   (see `peka/tags`_ for valid values for ``<tag>``)


.. |downloads_peka| image:: https://img.shields.io/conda/dn/bioconda/peka.svg?style=flat
   :target: https://anaconda.org/bioconda/peka
   :alt:   (downloads)
.. |docker_peka| image:: https://quay.io/repository/biocontainers/peka/status
   :target: https://quay.io/repository/biocontainers/peka
.. _`peka/tags`: https://quay.io/repository/biocontainers/peka?tab=tags


.. raw:: html

    <script>
        var package = "peka";
        var versions = ["1.0.0","0.1.6","0.1.5","0.1.4","0.1.2"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/peka/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/peka/README.html