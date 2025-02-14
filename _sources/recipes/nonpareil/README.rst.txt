:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'nonpareil'
.. highlight: bash

nonpareil
=========

.. conda:recipe:: nonpareil
   :replaces_section_title:
   :noindex:

   Estimate average coverage and create curves for metagenomic datasets

   :homepage: http://nonpareil.readthedocs.io/
   :developer docs: https://github.com/lmrodriguezr/nonpareil
   :license: Artistic License 2.0
   :recipe: /`nonpareil <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nonpareil>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/nonpareil/meta.yaml>`_

   


.. conda:package:: nonpareil

   |downloads_nonpareil| |docker_nonpareil|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>3.4.1-4</code>,  <code>3.4.1-3</code>,  <code>3.4.1-2</code>,  <code>3.4.1-1</code>,  <code>3.4.1-0</code>,  <code>3.4.0-1</code>,  <code>3.4.0-0</code>,  <code>3.3.4-2</code>,  <code>3.3.4-1</code>,  </span></summary>
      

      ``3.4.1-4``,  ``3.4.1-3``,  ``3.4.1-2``,  ``3.4.1-1``,  ``3.4.1-0``,  ``3.4.0-1``,  ``3.4.0-0``,  ``3.3.4-2``,  ``3.3.4-1``,  ``3.3.4-0``,  ``3.3.3-2``,  ``3.3.3-1``,  ``3.3.3-0``,  ``3.3.1-0``,  ``3.2-0``,  ``3.1.1-0``,  ``2.4.01-0``,  ``2.4-0``

      
      .. raw:: html

         </details>
      

   
   :depends libgcc-ng: ``>=12``
   :depends libstdcxx-ng: ``>=12``
   :depends r-base: ``>=4.2,<4.3.0a0``
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

      mamba install nonpareil

   and update with::

      mamba update nonpareil

  To create a new environment, run::

      mamba create --name myenvname nonpareil

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/nonpareil:<tag>

   (see `nonpareil/tags`_ for valid values for ``<tag>``)


.. |downloads_nonpareil| image:: https://img.shields.io/conda/dn/bioconda/nonpareil.svg?style=flat
   :target: https://anaconda.org/bioconda/nonpareil
   :alt:   (downloads)
.. |docker_nonpareil| image:: https://quay.io/repository/biocontainers/nonpareil/status
   :target: https://quay.io/repository/biocontainers/nonpareil
.. _`nonpareil/tags`: https://quay.io/repository/biocontainers/nonpareil?tab=tags


.. raw:: html

    <script>
        var package = "nonpareil";
        var versions = ["3.4.1","3.4.1","3.4.1","3.4.1","3.4.1"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/nonpareil/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/nonpareil/README.html