:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'mashmap'
.. highlight: bash

mashmap
=======

.. conda:recipe:: mashmap
   :replaces_section_title:
   :noindex:

   A fast approximate aligner for long DNA sequences.

   :homepage: https://github.com/marbl/MashMap
   :license: Custom
   :recipe: /`mashmap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mashmap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mashmap/meta.yaml>`_

   


.. conda:package:: mashmap

   |downloads_mashmap| |docker_mashmap|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>3.1.2-0</code>,  <code>3.1.1-0</code>,  <code>3.1.0-0</code>,  <code>3.0.6-0</code>,  <code>3.0.5-0</code>,  <code>3.0.4-0</code>,  <code>3.0.2-0</code>,  <code>3.0.1-1</code>,  <code>3.0.1-0</code>,  </span></summary>
      

      ``3.1.2-0``,  ``3.1.1-0``,  ``3.1.0-0``,  ``3.0.6-0``,  ``3.0.5-0``,  ``3.0.4-0``,  ``3.0.2-0``,  ``3.0.1-1``,  ``3.0.1-0``,  ``3.0-0``,  ``2.0-8``,  ``2.0-7``,  ``2.0-6``,  ``2.0-5``,  ``2.0-4``,  ``2.0-3``,  ``2.0-2``,  ``2.0-1``,  ``2.0-0``,  ``1.0-1``,  ``1.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends gsl: ``>=2.7,<2.8.0a0``
   :depends htslib: ``>=1.18,<1.20.0a0``
   :depends libgcc-ng: ``>=12``
   :depends libstdcxx-ng: ``>=12``
   :depends libzlib: ``>=1.2.13,<1.3.0a0``
   :depends openblas: 
   :depends zlib: 
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

      mamba install mashmap

   and update with::

      mamba update mashmap

  To create a new environment, run::

      mamba create --name myenvname mashmap

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/mashmap:<tag>

   (see `mashmap/tags`_ for valid values for ``<tag>``)


.. |downloads_mashmap| image:: https://img.shields.io/conda/dn/bioconda/mashmap.svg?style=flat
   :target: https://anaconda.org/bioconda/mashmap
   :alt:   (downloads)
.. |docker_mashmap| image:: https://quay.io/repository/biocontainers/mashmap/status
   :target: https://quay.io/repository/biocontainers/mashmap
.. _`mashmap/tags`: https://quay.io/repository/biocontainers/mashmap?tab=tags


.. raw:: html

    <script>
        var package = "mashmap";
        var versions = ["3.1.2","3.1.1","3.1.0","3.0.6","3.0.5"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/mashmap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/mashmap/README.html