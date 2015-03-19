# juliaopt-notebooks
A collection of IJulia notebooks related to optimization

[NBViewer link](http://nbviewer.ipython.org/github/JuliaOpt/juliaopt-notebooks/tree/master/notebooks/)

This is a work in progress.

Notebooks should be posted in format 3 (compatible with IPython pre 3.0),
until IPython 3.0 is distributed with standard binaries.
Here's a example of how to convert between versions:
```python
import IPython.nbformat
notebook = IPython.nbformat.read(open('JuMP-NetRevMgmt.ipynb','r'),4)
IPython.nbformat.write(notebook,open('JuMP-NetRevMgmt-3.ipynb','w'),3)
```
