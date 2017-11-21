# graphviz4all

A container with graphviz (http://www.graphviz.org/) executables (dot, circo, etc). 

This is for Singularity 2.4 at least and is available on singularity-hub


::

    singularity pull --name graphviz.img shub://cokelaer/graphviz4all:v1

Conversion of the dot file into SVG conterpart::

    ./graphviz.img dot -Tsvg test.dot -o test.svg
