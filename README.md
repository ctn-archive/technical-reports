technical-reports
=================

A collection of technical reports published by the CTN.

Install notes
-------------
TODO: how to install IPython.

Adding or modifying notebooks
-----------------------------
When creating a new notebook, create a branch (off of `master`) for it. You can then work on the notebook in this branch. When you wish to "publish" your work, *merge* your branch into `master`, effectively squashing your branch history. Give the merge commit a useful description of your notebook (first merge), or what changes you've made to it (subsequent merges). We still need a way to give DOIs for each time you "publish".

TODO
----
- Add .ipynb to .html conversion script, and have it run automatically on commit (like in Nengo). We want people to be able to read the notebooks without having IPython installed.
- Add custom .css for text formatting. The font size could be a bit larger, there could be more distinction between different headings (in terms of size).
