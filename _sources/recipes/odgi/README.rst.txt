:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'odgi'
.. highlight: bash

odgi
====

.. conda:recipe:: odgi
   :replaces_section_title:
   :noindex:

   An optimized dynamic genome\/graph implementation

   :homepage: https://github.com/pangenome/odgi
   :license: MIT
   :recipe: /`odgi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/odgi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/odgi/meta.yaml>`_

   


.. conda:package:: odgi

   |downloads_odgi| |docker_odgi|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.8.3-0</code>,  <code>0.8.2-0</code>,  <code>0.8.1-0</code>,  <code>0.8.0-0</code>,  <code>0.7.3-1</code>,  <code>0.7.3-0</code>,  <code>0.7.2-1</code>,  <code>0.7.2-0</code>,  <code>0.7.1-0</code>,  </span></summary>
      

      ``0.8.3-0``,  ``0.8.2-0``,  ``0.8.1-0``,  ``0.8.0-0``,  ``0.7.3-1``,  ``0.7.3-0``,  ``0.7.2-1``,  ``0.7.2-0``,  ``0.7.1-0``,  ``0.7.0-0``,  ``0.6.3-1``,  ``0.6.3-0``,  ``0.6.2-0``,  ``0.6.1-0``,  ``0.6-1``,  ``0.6-0``,  ``0.4.1-1``,  ``0.4.1-0``,  ``0.3-1``,  ``0.3-0``,  ``0.2-0``,  ``v0.3-0``

      
      .. raw:: html

         </details>
      

   
   :depends _openmp_mutex: ``>=4.5``
   :depends libgcc-ng: ``>=12``
   :depends libjemalloc: ``>=5.3.0``
   :depends libstdcxx-ng: ``>=12``
   :depends libzlib: ``>=1.2.13,<1.3.0a0``
   :depends pybind11: 
   :depends python: ``>=3.10,<3.11.0a0``
   :depends python_abi: ``3.10.* *_cp310``
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

      mamba install odgi

   and update with::

      mamba update odgi

  To create a new environment, run::

      mamba create --name myenvname odgi

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/odgi:<tag>

   (see `odgi/tags`_ for valid values for ``<tag>``)


.. |downloads_odgi| image:: https://img.shields.io/conda/dn/bioconda/odgi.svg?style=flat
   :target: https://anaconda.org/bioconda/odgi
   :alt:   (downloads)
.. |docker_odgi| image:: https://quay.io/repository/biocontainers/odgi/status
   :target: https://quay.io/repository/biocontainers/odgi
.. _`odgi/tags`: https://quay.io/repository/biocontainers/odgi?tab=tags


.. raw:: html

    <script>
        var package = "odgi";
        var versions = ["0.8.3","0.8.2","0.8.1","0.8.0","0.7.3"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/odgi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/odgi/README.html