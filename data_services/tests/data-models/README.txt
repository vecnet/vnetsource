To check the consistency of the Django data models in data_services/models.py
with the actual database tables, run the *nix shell script "make-canonical.sh"
in a terminal window in this directory.  The script produces two files in this
directory:

  models-canonical.py -- canonical form of the models.py file

  models-canonical-inspectdb -- canonical form of the data-models code that's
                                generated by inspecting the database

In PyCharm, visually compare the two files (select both files together, and
then from the pop-up context menu, select "Compare Two Files").  There is a
keyboard shortcut (on OS X, Command-D).