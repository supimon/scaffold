scaffold README
==================

Getting Started
---------------

- cd <directory containing this file>

- $VENV/bin/pip install -e .

- $VENV/bin/pserve development.ini


run setup.py first to install the project
---------------------------------------------
 - to run the setup.py
 - go to Tools > Run setup.py > from the dropdown list - select “develop” > click ok in the command bar that appears
 (yes - no need to type in anything)

always run setup.py after making any changes to it since this will update the egg info which will be used by the
--------------------------------------------------
pserve server for detecting entry points