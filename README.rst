gumpy
=====

``gumpy`` is a Python 3 toolbox to develop Brain-Computer Interfaces (BCI).

``gumpy`` contains implementations of several functions that are commonly used
during EEG and EMG decoding. For this purpose it heavily relies on other
numerical and scientific libraries, for instance ``numpy``, ``scipy``, or
``scikit-learn``, to name just a few. In fact, ``gumpy`` mostly wraps existing
functions in such a way that researchers working in the field can quickly
perform data analysis and implement novel classifiers. Moreover, one of
``gumpy``'s design principles was to make it easily extendable.

:license: MIT License
:contributions: Please use github (www.github.com/gumpy-bci/gumpy) and see below
:issues: Please use the issue tracker on github (www.github.com/gumpy-bci/gumpy/issues)


Documentation
=============

You can find documentation for gumpy either on www.gumpy.org or in subfolder
``doc``. For examples, see the folder ``examples``.


Contributing
============

If you wish to contribute to gumpy's development clone the main repository from
github and start coding, test if everything works as expected, and finally
submit patches or open merge requests. Preferrably in this order.

Please make sure that you follow PEP8, or have a look at the formatting of
gumpy's code, and include proper documentation both in your commit messages as
well as the source code. We use Google docstrings for formatting, and
auto-generate parts of the documentation with sphinx.


gumpy core developers and contributors
======================================
* Zied Tayeb
* Nicolai Waniek, www.github.com/rochus
* Juri Fedjae
* Leonard Richly


How to cite gumpy
=================

Zied Tayeb, Nicolai Waniek, Juri Fedjaev, Nejla Ghaboosi, Leonard Rychly,
Christian Widderich, Christoph Richter, Jörg Conradt. "gumpy: A Python Toolbox
Suitable for Hybrid Brain-Computer Interfaces"


.. code:: latex

    @Article{gumpy2018,
        Title = {gumpy: A Python Toolbox Suitable for Hybrid Brain-Computer Interfaces},
        Author = {Tayeb, Zied and Waniek, Nicolai and Fedjaev, Juri and Ghaboosi, Nejla and Rychly, Leonard and Widderich, Christian and Richter, Christoph and Conradt, Jorg},
        Year = {2018},
        Journal = {}
    }


Additional References
=====================

* www.gumpy.org: gumpy's main website. You can find links to datasets here
* www.github.com/gumpy-bci/gumpy: gumpy's main github repository
* www.github.com/gumpy-bci/gumpy-deeplearning: gumpy's deep learning models for BCI
* https://www.youtube.com/watch?v=M68GeL8PafE

License
=======

* All code in this repository is published under the MIT License.
  For more details see the LICENSE file.


