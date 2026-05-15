Self-contained Python packages of Regina
========================================

The program `Regina`_ is a powerful tool for studying low-dimensional
topology. It comes with a full `Python`_ interface that lets one
interact with it programmatically without writing any C++ code. 

The program `Tnorm` requires Regina 6.X as a dependency, since Regina >=7 does not
support transversely oriented spun normal surfaces. Since version 6.X of Regina is 
no longer maintained elsewhere, this repo is an attempt to maintain Regina 6.X in a 
form that will allow Tnorm to use it as a dependency. 

This package has been tested with SageMath’s Python 3.11 on macOS ARM64.
It may build under non-Sage Python 3.10/3.11 environments with the required
system dependencies installed, but those configurations are not currently tested.

It is not recommended to install this version of Regina directly. For a current version of Regina that can easily be installed in Python or Sage, https://github.com/3-manifolds/regina_wheels is a better option.

License
-------

Copyright Ben Burton, Ryan Budney, William Pettersson, Marc Culler,
Nathan M. Dunfield, Matthias Goerner, and others 1999-present. This
code is released under the `GNU General Public License, version 2`_ or
(at your option) any later version as published by the Free Software
Foundation.

.. _Regina: https://regina-normal.github.io/
.. _Python: https://python.org
.. _PyPI: https://pypi.org
.. _main docs: https://regina-normal.github.io/#docs
.. _sageRegina: https://sageregina.unhyperbolic.org
.. _SageMath: https://sagemath.org
.. _GitHub site: https://github.com/wtworden/sage-regina-6/
.. _GNU General Public License, version 2: https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt
