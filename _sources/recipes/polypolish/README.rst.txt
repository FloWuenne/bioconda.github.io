:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'polypolish'
.. highlight: bash

polypolish
==========

.. conda:recipe:: polypolish
   :replaces_section_title:
   :noindex:

   Polishing genome assemblies with short reads.

   :homepage: https://github.com/rrwick/Polypolish
   :license: GPL / GPLv3
   :recipe: /`polypolish <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/polypolish>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/polypolish/meta.yaml>`_

   


.. conda:package:: polypolish

   |downloads_polypolish| |docker_polypolish|

   :versions:
      
      

      ``0.5.0-4``,  ``0.5.0-3``,  ``0.5.0-2``,  ``0.5.0-1``,  ``0.5.0-0``

      

   
   :depends libgcc-ng: ``>=12``
   :depends libstdcxx-ng: ``>=12``
   :depends python: ``>=3.6``
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

      mamba install polypolish

   and update with::

      mamba update polypolish

  To create a new environment, run::

      mamba create --name myenvname polypolish

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/polypolish:<tag>

   (see `polypolish/tags`_ for valid values for ``<tag>``)


.. |downloads_polypolish| image:: https://img.shields.io/conda/dn/bioconda/polypolish.svg?style=flat
   :target: https://anaconda.org/bioconda/polypolish
   :alt:   (downloads)
.. |docker_polypolish| image:: https://quay.io/repository/biocontainers/polypolish/status
   :target: https://quay.io/repository/biocontainers/polypolish
.. _`polypolish/tags`: https://quay.io/repository/biocontainers/polypolish?tab=tags


.. raw:: html

    <script>
        var package = "polypolish";
        var versions = ["0.5.0","0.5.0","0.5.0","0.5.0","0.5.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/polypolish/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/polypolish/README.html