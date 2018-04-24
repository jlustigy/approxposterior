Installation
============

:py:obj:`approxposterior` can be installed by either using :py:obj:`pip` or
directly from source.

Using :py:obj:`pip`:

.. code-block:: bash

   pip install approxposterior

This step can fail if george (the Python Gaussian Process package) is not properly installed.
To install george, run

.. code-block:: bash

    conda install -c conda-forge george

then pip install :py:obj:`approxposterior`.

To upgrade:

.. code-block:: bash

   pip install -U --no-deps approxposterior

From source:

.. code-block:: bash

  git clone git@github.com:dflemin3/approxposterior.git
  cd approxposterior
  python setup.py install

Coming soon, you will be able to install :py:obj:`approxposterior` via conda-forge!