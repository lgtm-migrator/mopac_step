=======
History
=======
2022.11.18 -- Printing spins on atoms
  Fixed an oversight that preventing priniting spins on the atoms, and storing them on
  the structure. Also increased the precision of the AUX file so have coordinates to
  seven decimals, which should maintain symmstry better.
  
2022.11.4 -- Added ForceConstant substep
  Calculates and writes the Hessian (force constant) matrix to disk. Works for both
  molecular and periodic systems, and provides an option to control which parts of the
  Hessian matrix are written. Defaults to the full matrix. Also provides options to
  control the units of the output, with default of N/m for the atom block of the
  Hessian as well as the atom-cell off-diagonal block, and GPa for the cell block.

2021.2.11 (11 February 2021)
----------------------------

* Updated the README file to give a better description.
* Updated the short description in setup.py to work with the new installer.
* Added keywords for better searchability.

2021.2.4 (4 February 2021)
--------------------------

* Updated for compatibility with the new system classes in MolSystem
  2021.2.2 release.

2020.12.5 (5 December 2020)
---------------------------

* Internal: switching CI from TravisCI to GitHub Actions, and in the
  process moving documentation from ReadTheDocs to GitHub Pages where
  it is consolidated with the main SEAMM documentation.

2020.11.2 (2 November 2020)
---------------------------

* Updated to be compatible with the new command-line argument
  handling.

2020.10.7 (7 October 2020)
----------------------------

* Updated to handle citations using the new framework.

2020.9.29 (29 September 2020)
-----------------------------

* Updated to be compatible with the new system classes in MolSystem.

2020.8.1 (1 August 2020)
------------------------

* Fixed bug caused by coordinates being strings, not numbers, in some
  cases.

2020.7.0 (23 July 2020)
-----------------------

* Improved the text output when running.

0.9 (15 April 2020)
-------------------

* General bug fixes and cleanup of the code.

0.7.0 (17 December 2019)
------------------------

* Consolidating minor changes and making a uniform release at year's
  end.

0.5.1 (29 August 2019)
----------------------

* First version that runs correctly and generates output.

0.2.0 (13 August 2019)
----------------------

* First release on PyPI.
