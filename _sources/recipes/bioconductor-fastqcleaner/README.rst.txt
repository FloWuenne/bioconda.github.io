:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fastqcleaner'
.. highlight: bash

bioconductor-fastqcleaner
=========================

.. conda:recipe:: bioconductor-fastqcleaner
   :replaces_section_title:
   :noindex:

   A Shiny Application for Quality Control\, Filtering and Trimming of FASTQ Files

   :homepage: https://bioconductor.org/packages/3.18/bioc/html/FastqCleaner.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-fastqcleaner <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fastqcleaner>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fastqcleaner/meta.yaml>`_

   An interactive web application for quality control\, filtering and trimming of FASTQ files. This user\-friendly tool combines a pipeline for data processing based on Biostrings and ShortRead infrastructure\, with a cutting\-edge visual environment. Single\-Read and Paired\-End files can be locally processed. Diagnostic interactive plots \(CG content\, per\-base sequence quality\, etc.\) are provided for both the input and output files.


.. conda:package:: bioconductor-fastqcleaner

   |downloads_bioconductor-fastqcleaner| |docker_bioconductor-fastqcleaner|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.20.0-0</code>,  <code>1.18.0-0</code>,  <code>1.16.0-1</code>,  <code>1.16.0-0</code>,  <code>1.12.0-2</code>,  <code>1.12.0-1</code>,  <code>1.12.0-0</code>,  <code>1.10.0-0</code>,  <code>1.8.0-1</code>,  </span></summary>
      

      ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-1``,  ``1.16.0-0``,  ``1.12.0-2``,  ``1.12.0-1``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.0.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-biostrings: ``>=2.70.0,<2.71.0``
   :depends bioconductor-biostrings: ``>=2.70.1,<2.71.0a0``
   :depends bioconductor-iranges: ``>=2.36.0,<2.37.0``
   :depends bioconductor-iranges: ``>=2.36.0,<2.37.0a0``
   :depends bioconductor-s4vectors: ``>=0.40.0,<0.41.0``
   :depends bioconductor-s4vectors: ``>=0.40.2,<0.41.0a0``
   :depends bioconductor-shortread: ``>=1.60.0,<1.61.0``
   :depends bioconductor-shortread: ``>=1.60.0,<1.61.0a0``
   :depends libblas: ``>=3.9.0,<4.0a0``
   :depends libgcc-ng: ``>=12``
   :depends liblapack: ``>=3.9.0,<4.0a0``
   :depends libstdcxx-ng: ``>=12``
   :depends r-base: ``>=4.3,<4.4.0a0``
   :depends r-dt: 
   :depends r-htmltools: 
   :depends r-rcpp: ``>=0.12.12``
   :depends r-shiny: 
   :depends r-shinybs: 
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

      mamba install bioconductor-fastqcleaner

   and update with::

      mamba update bioconductor-fastqcleaner

  To create a new environment, run::

      mamba create --name myenvname bioconductor-fastqcleaner

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fastqcleaner:<tag>

   (see `bioconductor-fastqcleaner/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fastqcleaner| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fastqcleaner.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fastqcleaner
   :alt:   (downloads)
.. |docker_bioconductor-fastqcleaner| image:: https://quay.io/repository/biocontainers/bioconductor-fastqcleaner/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fastqcleaner
.. _`bioconductor-fastqcleaner/tags`: https://quay.io/repository/biocontainers/bioconductor-fastqcleaner?tab=tags


.. raw:: html

    <script>
        var package = "bioconductor-fastqcleaner";
        var versions = ["1.20.0","1.18.0","1.16.0","1.16.0","1.12.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fastqcleaner/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fastqcleaner/README.html