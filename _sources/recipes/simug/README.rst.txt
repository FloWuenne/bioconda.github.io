:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'simug'
.. highlight: bash

simug
=====

.. conda:recipe:: simug
   :replaces_section_title:
   :noindex:

   A simple\, flexible\, and powerful tool to simulate genome sequences with pre\-defined or random genomic variants.

   :homepage: https://github.com/yjx1217/simuG
   :license: MIT / MIT
   :recipe: /`simug <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/simug>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/simug/meta.yaml>`_

   


.. conda:package:: simug

   |downloads_simug| |docker_simug|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends gzip: 
   :depends perl: ``*``
   :depends perl-getopt-long: 
   :depends perl-list-util: 
   :depends perl-pod-usage: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install simug

   and update with::

      conda update simug

   or use the docker container::

      docker pull quay.io/biocontainers/simug:<tag>

   (see `simug/tags`_ for valid values for ``<tag>``)


.. |downloads_simug| image:: https://img.shields.io/conda/dn/bioconda/simug.svg?style=flat
   :target: https://anaconda.org/bioconda/simug
   :alt:   (downloads)
.. |docker_simug| image:: https://quay.io/repository/biocontainers/simug/status
   :target: https://quay.io/repository/biocontainers/simug
.. _`simug/tags`: https://quay.io/repository/biocontainers/simug?tab=tags


.. raw:: html

    <script>
        var package = "simug";
        var versions = ["1.0.0","1.0.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/simug/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/simug/README.html