# calypso_auto_split
Running CALYPSO structure search with Split mode automatically on cluster.

[CALYPSO](www.calypso.cn) is a high performance structure prediction method and software. It requires only chemical compositions of given compounds under aim pressure or temperature to predict stable or metastable structures. 
Two key steps in CALYPSO are structure generation and structure optimization, however structure optimization is too time consume. So for accelatrating CALYPSO structure search, optimization tasks should be parallelly performed on different compute node.
The aim of this package is to run CALYPSO with Split mode automatically, and all prediction step are contralled by python scrapts.

CALYPSO has written in python2 and did not tansfer to python3
so run it in a conda virtual enveronment with python2 or just use $ python2 caly_auto_split.py
