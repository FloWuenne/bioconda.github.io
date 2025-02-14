:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'tsv-utils'
.. highlight: bash

tsv-utils
=========

.. conda:recipe:: tsv-utils
   :replaces_section_title:
   :noindex:

   eBay\'s TSV Utilities

   :homepage: https://github.com/eBay/tsv-utils
   :documentation: https://ebay.github.io/tsv-utils/
   
   :developer docs: https://github.com/eBay/tsv-utils#obtaining-and-installation
   :license: BSL-1.0
   :recipe: /`tsv-utils <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tsv-utils>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tsv-utils/meta.yaml>`_

   Command line tools for large\, tabular data files. 
   Filtering\, statistics\, sampling\, joins and more.



.. conda:package:: tsv-utils

   |downloads_tsv-utils| |docker_tsv-utils|

   :versions:
      
      

      ``2.2.0-0``

      

   
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

      mamba install tsv-utils

   and update with::

      mamba update tsv-utils

  To create a new environment, run::

      mamba create --name myenvname tsv-utils

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/tsv-utils:<tag>

   (see `tsv-utils/tags`_ for valid values for ``<tag>``)


.. |downloads_tsv-utils| image:: https://img.shields.io/conda/dn/bioconda/tsv-utils.svg?style=flat
   :target: https://anaconda.org/bioconda/tsv-utils
   :alt:   (downloads)
.. |docker_tsv-utils| image:: https://quay.io/repository/biocontainers/tsv-utils/status
   :target: https://quay.io/repository/biocontainers/tsv-utils
.. _`tsv-utils/tags`: https://quay.io/repository/biocontainers/tsv-utils?tab=tags


.. raw:: html

    <script>
        var package = "tsv-utils";
        var versions = ["2.2.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/tsv-utils/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/tsv-utils/README.html