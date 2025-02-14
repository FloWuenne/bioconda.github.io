:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'ms2query'
.. highlight: bash

ms2query
========

.. conda:recipe:: ms2query
   :replaces_section_title:
   :noindex:

   Reliable and fast MS\/MS spectral\-based analogue search

   :homepage: https://github.com/iomega/ms2query
   :license: Apache-2.0
   :recipe: /`ms2query <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ms2query>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/ms2query/meta.yaml>`_
   :links: doi: :doi:`https://doi.org/10.1038/s41467-023-37446-4`

   


.. conda:package:: ms2query

   |downloads_ms2query| |docker_ms2query|

   :versions:
      
      

      ``1.2.3-0``,  ``1.2.2-0``,  ``1.2.1-0``,  ``1.2.0-0``

      

   
   :depends gensim: ``>=4.0.0``
   :depends h5py: ``>=3.8.0``
   :depends matchms: ``>=0.14.0,<=0.17.0``
   :depends matchmsextras: ``0.4.1.*``
   :depends matplotlib-base: 
   :depends ms2deepscore: 
   :depends onnxruntime: 
   :depends pandas: ``>=1.2.5,<2.0.0``
   :depends pubchempy: 
   :depends python: ``>=3.7``
   :depends rdkit: 
   :depends scikit-learn: 
   :depends skl2onnx: 
   :depends spec2vec: ``>=0.6.0``
   :depends tensorflow: ``<2.9``
   :depends tqdm: 
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

      mamba install ms2query

   and update with::

      mamba update ms2query

  To create a new environment, run::

      mamba create --name myenvname ms2query

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/ms2query:<tag>

   (see `ms2query/tags`_ for valid values for ``<tag>``)


.. |downloads_ms2query| image:: https://img.shields.io/conda/dn/bioconda/ms2query.svg?style=flat
   :target: https://anaconda.org/bioconda/ms2query
   :alt:   (downloads)
.. |docker_ms2query| image:: https://quay.io/repository/biocontainers/ms2query/status
   :target: https://quay.io/repository/biocontainers/ms2query
.. _`ms2query/tags`: https://quay.io/repository/biocontainers/ms2query?tab=tags


.. raw:: html

    <script>
        var package = "ms2query";
        var versions = ["1.2.3","1.2.2","1.2.1","1.2.0"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/ms2query/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/ms2query/README.html