:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'vrhyme'
.. highlight: bash

vrhyme
======

.. conda:recipe:: vrhyme
   :replaces_section_title:
   :noindex:

   Binning Virus Genomes from Metagenomes.

   :homepage: https://github.com/AnantharamanLab/vRhyme
   :license: GPL / GPL-3.0
   :recipe: /`vrhyme <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vrhyme>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/vrhyme/meta.yaml>`_
   :links: doi: :doi:`10.1093/nar/gkac341`

   


.. conda:package:: vrhyme

   |downloads_vrhyme| |docker_vrhyme|

   :versions:
      
      

      ``1.1.0-1``,  ``1.1.0-0``

      

   
   :depends bowtie2: 
   :depends bwa: 
   :depends mash: 
   :depends mmseqs2: 
   :depends networkx: 
   :depends numba: 
   :depends numpy: 
   :depends pandas: 
   :depends prodigal: 
   :depends pysam: 
   :depends python: ``>=3.6``
   :depends samtools: 
   :depends scikit-learn: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install vrhyme

   and update with::

      conda update vrhyme

   or use the docker container::

      docker pull quay.io/biocontainers/vrhyme:<tag>

   (see `vrhyme/tags`_ for valid values for ``<tag>``)


.. |downloads_vrhyme| image:: https://img.shields.io/conda/dn/bioconda/vrhyme.svg?style=flat
   :target: https://anaconda.org/bioconda/vrhyme
   :alt:   (downloads)
.. |docker_vrhyme| image:: https://quay.io/repository/biocontainers/vrhyme/status
   :target: https://quay.io/repository/biocontainers/vrhyme
.. _`vrhyme/tags`: https://quay.io/repository/biocontainers/vrhyme?tab=tags


.. raw:: html

    <script>
        var package = "vrhyme";
        var versions = ["1.1.0","1.1.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/vrhyme/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/vrhyme/README.html