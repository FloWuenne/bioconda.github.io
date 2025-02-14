:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'perl-compress-bgzf'
.. highlight: bash

perl-compress-bgzf
==================

.. conda:recipe:: perl-compress-bgzf/0.005
   :replaces_section_title:
   :noindex:

   Read\/write blocked GZIP \(BGZF\) files

   :homepage: http://metacpan.org/pod/Compress::BGZF
   :license: gpl_3
   :recipe: /`perl-compress-bgzf <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-compress-bgzf>`_/`0.005 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-compress-bgzf/0.005>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/perl-compress-bgzf/0.005/meta.yaml>`_

   


.. conda:package:: perl-compress-bgzf

   |downloads_perl-compress-bgzf| |docker_perl-compress-bgzf|

   :versions:
      
      

      ``0.005-1``,  ``0.005-0``

      

   
   :depends perl: ``>=5.32.1,<6.0a0 *_perl5``
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

      mamba install perl-compress-bgzf

   and update with::

      mamba update perl-compress-bgzf

  To create a new environment, run::

      mamba create --name myenvname perl-compress-bgzf

  with ``myenvname`` being a reasonable name for the environment
  (see e.g. the `mamba docs <https://mamba.readthedocs.io>`_ for details and further options).

  Alternatively, use the docker container::

      docker pull quay.io/biocontainers/perl-compress-bgzf:<tag>

   (see `perl-compress-bgzf/tags`_ for valid values for ``<tag>``)


.. |downloads_perl-compress-bgzf| image:: https://img.shields.io/conda/dn/bioconda/perl-compress-bgzf.svg?style=flat
   :target: https://anaconda.org/bioconda/perl-compress-bgzf
   :alt:   (downloads)
.. |docker_perl-compress-bgzf| image:: https://quay.io/repository/biocontainers/perl-compress-bgzf/status
   :target: https://quay.io/repository/biocontainers/perl-compress-bgzf
.. _`perl-compress-bgzf/tags`: https://quay.io/repository/biocontainers/perl-compress-bgzf?tab=tags


.. raw:: html

    <script>
        var package = "perl-compress-bgzf";
        var versions = ["0.005","0.005"];
    </script>






Download stats
-----------------

.. raw:: html
    :file: ../../templates/package_dashboard.html

Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/perl-compress-bgzf/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/perl-compress-bgzf/README.html