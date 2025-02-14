:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'assembly_finder'
.. highlight: bash

assembly_finder
===============

.. conda:recipe:: assembly_finder
   :replaces_section_title:
   :noindex:

   Snakemake pipeline to download assemblies from NCBI.

   :homepage: https://github.com/metagenlab/assembly_finder
   :license: GPL-3.0-or-later
   :recipe: /`assembly_finder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/assembly_finder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/assembly_finder/meta.yaml>`_

   


.. conda:package:: assembly_finder

   |downloads_assembly_finder| |docker_assembly_finder|

   :versions:
      
      

      ``0.4.1-0``,  ``0.4.0-0``,  ``0.3.3-1``,  ``0.3.3-0``,  ``0.3.2-1``,  ``0.3.2-0``,  ``0.3.1-0``

      

   
   :depends aspera-cli: ``>=4.14.0``
   :depends biopython: ``>=1.78``
   :depends click: ``>=7``
   :depends ete3: ``>=3.1.3``
   :depends pandas: ``>=2.0.3``
   :depends python: ``>=3.9,<3.12``
   :depends snakemake-minimal: ``>=7.32.4``
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

      mamba install assembly_finder

   and update with::

      mamba update assembly_finder

  To create a new environment, run::

      mamba create --name myenvname assembly_finder

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/assembly_finder:<tag>

   (see `assembly_finder/tags`_ for valid values for ``<tag>``)


.. |downloads_assembly_finder| image:: https://img.shields.io/conda/dn/bioconda/assembly_finder.svg?style=flat
   :target: https://anaconda.org/bioconda/assembly_finder
   :alt:   (downloads)
.. |docker_assembly_finder| image:: https://quay.io/repository/biocontainers/assembly_finder/status
   :target: https://quay.io/repository/biocontainers/assembly_finder
.. _`assembly_finder/tags`: https://quay.io/repository/biocontainers/assembly_finder?tab=tags


.. raw:: html

    <script>
        var package = "assembly_finder";
        var versions = ["0.4.1","0.4.0","0.3.3","0.3.3","0.3.2"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/assembly_finder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/assembly_finder/README.html