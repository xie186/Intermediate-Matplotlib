Matplotlib API
==============


Functional
----------

`matplotlib.pyplot <https://matplotlib.org/api/_as_gen/matplotlib.pyplot.html#module-matplotlib.pyplot>`_
is a collection of command style functions that make Matplotlib work like MATLAB. Each pyplot function makes
some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a
plotting area, decorates the plot with labels, etc.

It is mainly intended for interactive plots and simple cases of programmatic plot generation.

**Further reading:**

* The `matplotlib.pyplot <https://matplotlib.org/api/_as_gen/matplotlib.pyplot.html#module-matplotlib.pyplot>`_
  function reference.
* `Pyplot tutorial <https://matplotlib.org/tutorials/introductory/pyplot.html>`_.
* `Pyplot examples <https://matplotlib.org/gallery/index.html#pyplots-examples>`_.


Object-Oriented API
-------------------

At its core, Matplotlib is object-oriented. We recommend directly working with the objects, if you need more
control and customization of your plots.

In many cases you will create a `Figure` and one or more `Axes` using `pyplot.subplots` and from then on only
work on these objects. However, it's also possible to create `Figure`s explicitly (e.g. when including them
in GUI applications).

**Further reading:**

* `matplotlib.axes.Axes` and `matplotlib.figure.Figure` for an overview of plotting functions.
* Most of the `examples <https://matplotlib.org/gallery/index.html#examples-index>`_ use the object-oriented
  approach (except for the pyplot section)