:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-clariomsmousehttranscriptcluster.db'
.. highlight: bash

bioconductor-clariomsmousehttranscriptcluster.db
================================================

.. conda:recipe:: bioconductor-clariomsmousehttranscriptcluster.db
   :replaces_section_title:
   :noindex:

   Affymetrix clariomsmouseht annotation data \(chip clariomsmousehttranscriptcluster\)

   :homepage: https://bioconductor.org/packages/3.18/data/annotation/html/clariomsmousehttranscriptcluster.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-clariomsmousehttranscriptcluster.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsmousehttranscriptcluster.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-clariomsmousehttranscriptcluster.db/meta.yaml>`_

   Affymetrix clariomsmouseht annotation data \(chip clariomsmousehttranscriptcluster\) assembled using data from public repositories


.. conda:package:: bioconductor-clariomsmousehttranscriptcluster.db

   |downloads_bioconductor-clariomsmousehttranscriptcluster.db| |docker_bioconductor-clariomsmousehttranscriptcluster.db|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>8.8.0-4</code>,  <code>8.8.0-3</code>,  <code>8.8.0-2</code>,  <code>8.8.0-1</code>,  <code>8.8.0-0</code>,  <code>8.7.0-7</code>,  <code>8.7.0-6</code>,  <code>8.7.0-5</code>,  <code>8.7.0-4</code>,  </span></summary>
      

      ``8.8.0-4``,  ``8.8.0-3``,  ``8.8.0-2``,  ``8.8.0-1``,  ``8.8.0-0``,  ``8.7.0-7``,  ``8.7.0-6``,  ``8.7.0-5``,  ``8.7.0-4``,  ``8.7.0-3``,  ``8.7.0-2``,  ``8.7.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-annotationdbi: ``>=1.64.0,<1.65.0``
   :depends bioconductor-data-packages: ``>=20231203``
   :depends bioconductor-org.mm.eg.db: ``>=3.18.0,<3.19.0``
   :depends curl: 
   :depends r-base: ``>=4.3,<4.4.0a0``
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

      mamba install bioconductor-clariomsmousehttranscriptcluster.db

   and update with::

      mamba update bioconductor-clariomsmousehttranscriptcluster.db

  To create a new environment, run::

      mamba create --name myenvname bioconductor-clariomsmousehttranscriptcluster.db

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db:<tag>

   (see `bioconductor-clariomsmousehttranscriptcluster.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-clariomsmousehttranscriptcluster.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-clariomsmousehttranscriptcluster.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-clariomsmousehttranscriptcluster.db
   :alt:   (downloads)
.. |docker_bioconductor-clariomsmousehttranscriptcluster.db| image:: https://quay.io/repository/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db
.. _`bioconductor-clariomsmousehttranscriptcluster.db/tags`: https://quay.io/repository/biocontainers/bioconductor-clariomsmousehttranscriptcluster.db?tab=tags


.. raw:: html

    <script>
        var package = "bioconductor-clariomsmousehttranscriptcluster.db";
        var versions = ["8.8.0","8.8.0","8.8.0","8.8.0","8.8.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-clariomsmousehttranscriptcluster.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-clariomsmousehttranscriptcluster.db/README.html