CpuGraph
========

Tool for profiling parallelism during compile-test loops.

Dependencies
------------

* Python3
* Psutil

Usage
-----

```
./cpugraph -- sleep 2 | gnuplot -p -e "set terminal dumb; plot '-' using 1:2 w l"
```
