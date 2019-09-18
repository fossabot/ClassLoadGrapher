[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmenzew%2FClassLoadGrapher.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmenzew%2FClassLoadGrapher?ref=badge_shield)

================
ClassloadGrapher
================

Is your Java program's startup too slow? have you wondered what classes are in your permgen/metaspace?
Well then, this tool can help provide the answer. It generates a tree of your application's class hierarchy. 


=======
To run:
=======

% java -XX:+TraceClassLoading -XX:+TraceClassUnloading -XX:+TraceClassResolution -jar your-jar.jar > ~/MyClassTraceFile.txt

% python classloadgrapher/clgrapher.py ~/MyClassTraceFile.txt ~/MyClassTraceFile.digraph


And in the same folder you will find a pdf file: ~/MyClassTraceFile.digraph.pdf

_____

==============
Sample output:
==============


.. image:: https://github.com/menzew/ClassLoadGrapher/blob/master/Sample-Screenshot.png


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmenzew%2FClassLoadGrapher.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmenzew%2FClassLoadGrapher?ref=badge_large)