.. _`augustus`:

augustus
========

|downloads|

AUGUSTUS is a gene prediction program for eukaryotes written by Mario Stanke and Oliver Keller. It can be used as an ab initio program\, which means it bases its prediction purely on the sequence. AUGUSTUS may also incorporate hints on the gene structure coming from extrinsic sources such as EST\, MS\/MS\, protein alignments and synthenic genomic alignments.

============= ===========
Home          http://bioinf.uni-greifswald.de/augustus/
Versions      3.3, 3.2.3, 3.2.2, 3.1
License       MIT
Recipe        https://github.com/bioconda/bioconda-recipes/tree/master/recipes//home/circleci/project/docs/bioconda-recipes/recipes/augustus/meta.yaml



Links         biotools: :biotools:`augustus`, doi: :doi:`10.1093/bioinformatics/btr010`

============= ===========



Installation
------------

.. highlight: bash

With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

   conda install augustus

and update with::

   conda update augustus


Notes
-----
Builds with sqlite support are currently only available on Linux due to compile issues with macOS


|docker|

A Docker container is available at https://quay.io/repository/biocontainers/augustus.

Link to this page
-----------------

Render an |badge| badge with the following Markdown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square)](http://bioconda.github.io/recipes/augustus/README.html)

.. |badge| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat-square
           :target: http://bioconda.github.io/recipes/augustus/README.html
.. |downloads| image:: https://anaconda.org/bioconda/augustus/badges/downloads.svg
               :target: https://anaconda.org/bioconda/augustus
.. |docker| image:: https://quay.io/repository/biocontainers/augustus/status
                :target: https://quay.io/repository/biocontainers/augustus

