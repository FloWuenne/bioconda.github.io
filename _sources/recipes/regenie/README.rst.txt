:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'regenie'
.. highlight: bash

regenie
=======

.. conda:recipe:: regenie
   :replaces_section_title:
   :noindex:

   Regenie is a C\+\+ program for whole genome regression modelling of large genome\-wide association studies \(GWAS\).

   :homepage: https://rgcgithub.github.io/regenie/
   :documentation: https://rgcgithub.github.io/regenie/options/
   
   :developer docs: https://github.com/rgcgithub/regenie
   :license: MIT
   :recipe: /`regenie <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/regenie>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/regenie/meta.yaml>`_

   


.. conda:package:: regenie

   |downloads_regenie| |docker_regenie|

   :versions:
      
      

      ``1.0.6.7-0``

      

   
   :depends bgenix: ``>=1.1.7``
   :depends blas: ``2.20 mkl``
   :depends boost-cpp: ``>=1.72.0,<1.72.1.0a0``
   :depends libgcc-ng: ``>=7.5.0``
   :depends libgfortran-ng: 
   :depends libgfortran4: ``>=7.5.0``
   :depends libstdcxx-ng: ``>=7.5.0``
   :depends llvm-openmp: 
   :depends mkl: ``>=2020.2,<2021.0a0``
   :depends mkl-include: 
   :depends sqlite: ``>=3.33.0,<4.0a0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :depends zstd: ``>=1.4.5,<1.5.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install regenie

   and update with::

      conda update regenie

   or use the docker container::

      docker pull quay.io/biocontainers/regenie:<tag>

   (see `regenie/tags`_ for valid values for ``<tag>``)


.. |downloads_regenie| image:: https://img.shields.io/conda/dn/bioconda/regenie.svg?style=flat
   :target: https://anaconda.org/bioconda/regenie
   :alt:   (downloads)
.. |docker_regenie| image:: https://quay.io/repository/biocontainers/regenie/status
   :target: https://quay.io/repository/biocontainers/regenie
.. _`regenie/tags`: https://quay.io/repository/biocontainers/regenie?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/regenie/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/regenie/README.html