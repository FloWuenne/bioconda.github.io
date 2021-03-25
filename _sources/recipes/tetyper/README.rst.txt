:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'tetyper'
.. highlight: bash

tetyper
=======

.. conda:recipe:: tetyper
   :replaces_section_title:
   :noindex:

   Typing of a specific transposable element \(TE\) of interest from paired\-end sequencing data.

   :homepage: https://github.com/aesheppard/TETyper
   :license: GPL-3.0
   :recipe: /`tetyper <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tetyper>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/tetyper/meta.yaml>`_
   :links: doi: :doi:`10.1099/mgen.0.000232`

   


.. conda:package:: tetyper

   |downloads_tetyper| |docker_tetyper|

   :versions:
      
      

      ``1.1-1``,  ``1.1-0``

      

   
   :depends bcftools: 
   :depends biopython: 
   :depends blast: 
   :depends bwa: 
   :depends pysam: 
   :depends python: 
   :depends pyvcf: 
   :depends samtools: 
   :depends spades: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install tetyper

   and update with::

      conda update tetyper

   or use the docker container::

      docker pull quay.io/biocontainers/tetyper:<tag>

   (see `tetyper/tags`_ for valid values for ``<tag>``)


.. |downloads_tetyper| image:: https://img.shields.io/conda/dn/bioconda/tetyper.svg?style=flat
   :target: https://anaconda.org/bioconda/tetyper
   :alt:   (downloads)
.. |docker_tetyper| image:: https://quay.io/repository/biocontainers/tetyper/status
   :target: https://quay.io/repository/biocontainers/tetyper
.. _`tetyper/tags`: https://quay.io/repository/biocontainers/tetyper?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/tetyper/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/tetyper/README.html