:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-enrichtf'
.. highlight: bash

bioconductor-enrichtf
=====================

.. conda:recipe:: bioconductor-enrichtf
   :replaces_section_title:
   :noindex:

   Transcription Factors Enrichment Analysis

   :homepage: https://bioconductor.org/packages/3.18/bioc/html/enrichTF.html
   :license: GPL-3
   :recipe: /`bioconductor-enrichtf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-enrichtf>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-enrichtf/meta.yaml>`_

   As transcription factors \(TFs\) play a crucial role in regulating the transcription process through binding on the genome alone or in a combinatorial manner\, TF enrichment analysis is an efficient and important procedure to locate the candidate functional TFs from a set of experimentally defined regulatory regions. While it is commonly accepted that structurally related TFs may have similar binding preference to sequences \(i.e. motifs\) and one TF may have multiple motifs\, TF enrichment analysis is much more challenging than motif enrichment analysis. Here we present a R package for TF enrichment analysis which combine motif enrichment with the PECA model.


.. conda:package:: bioconductor-enrichtf

   |downloads_bioconductor-enrichtf| |docker_bioconductor-enrichtf|

   :versions:
      
      

      ``1.16.0-0``,  ``1.14.0-0``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-1``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-1``

      

   
   :depends bioconductor-biocgenerics: ``>=0.46.0,<0.47.0``
   :depends bioconductor-bsgenome: ``>=1.68.0,<1.69.0``
   :depends bioconductor-clusterprofiler: ``>=4.8.0,<4.9.0``
   :depends bioconductor-genomeinfodb: ``>=1.36.0,<1.37.0``
   :depends bioconductor-genomicranges: ``>=1.52.0,<1.53.0``
   :depends bioconductor-iranges: ``>=2.34.0,<2.35.0``
   :depends bioconductor-jaspar2018: ``>=1.1.0,<1.2.0``
   :depends bioconductor-motifmatchr: ``>=1.22.0,<1.23.0``
   :depends bioconductor-pipeframe: ``>=1.16.0,<1.17.0``
   :depends bioconductor-rtracklayer: ``>=1.60.0,<1.61.0``
   :depends bioconductor-s4vectors: ``>=0.38.0,<0.39.0``
   :depends bioconductor-tfbstools: ``>=1.38.0,<1.39.0``
   :depends r-base: ``>=4.3,<4.4.0a0``
   :depends r-ggplot2: 
   :depends r-ggpubr: 
   :depends r-heatmap3: 
   :depends r-magrittr: 
   :depends r-r.utils: 
   :depends r-rmarkdown: 
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

      mamba install bioconductor-enrichtf

   and update with::

      mamba update bioconductor-enrichtf

  To create a new environment, run::

      mamba create --name myenvname bioconductor-enrichtf

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/bioconductor-enrichtf:<tag>

   (see `bioconductor-enrichtf/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-enrichtf| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-enrichtf.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-enrichtf
   :alt:   (downloads)
.. |docker_bioconductor-enrichtf| image:: https://quay.io/repository/biocontainers/bioconductor-enrichtf/status
   :target: https://quay.io/repository/biocontainers/bioconductor-enrichtf
.. _`bioconductor-enrichtf/tags`: https://quay.io/repository/biocontainers/bioconductor-enrichtf?tab=tags


.. raw:: html

    <script>
        var package = "bioconductor-enrichtf";
        var versions = ["1.16.0","1.14.0","1.10.0","1.8.0","1.6.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-enrichtf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-enrichtf/README.html