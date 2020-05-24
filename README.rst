GAT 1.3.6 has a bug by defaulting --ignore-track-segments=TRUE and doesn't accept False as an agrument. Here are the steps to fix this:

0) log into node w/ internet access
1) create a virtual env: conda create --name test_gat python=2.7
2) conda activate test_gat
3) 



The software is available for download on pypi:

    pip install gat

Please see http://gat.readthedocs.org/en/latest/ for a manual and tutorials.

A GAT user group is at:

https://groups.google.com/forum/?fromgroups#!forum/gat-user-group

The latest release can be downloaded from pypi at
https://pypi.python.org/pypi/gat
