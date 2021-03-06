# Scientific Python course

* [Introduction](#introduction)
* [Beginner Course](#beginner-course)
  * [Schedule](#beginner-schedule)
  * [Content](#beginner-content)
* [Advanced Course](#advanced-course)
  * [Schedule](#advanced-schedule)
  * [Content](#advanced-content)


## Introduction <a name="introduction"></a>

Lecture notes from the course taught at the [University of Bordeaux] in the
academic year 2017 for PhD students.  Each student needs to come with a
notebook computer running either Linux, OSX or Windows.  

![](XKCD.png) Adapted from https://xkcd.com/353/

|

The scientific Python ecosystem is made of several modules that constitute
together the scientific stack. There are hundreds of [Python scientific
packages] and most of them are built on top of numpy, scipy, matplotib, pandas,
cython and/or sympy. We won't cover everything in this short course, but you
should get enough information to decide if your research can benefit from
Python. And I bet it will likely do.

This course is mostly based on the teaching material kindly provided by:

* [Software Carpentry]
* [Scipy Lecture Notes]
* [From Python to Numpy]


## Beginner course <a name="beginner-course"></a>

### Schedule <a name="beginner-schedule"></a>

Day 1  | Monday February 6th, 2017      | 
------ | ------------------------------ |
09:00  | Installation & Welcome         |
09:15  | [Introduction]                 |
10:30  | *Coffee break*                 |
10:45  | [Introduction]                 |
12:00  | *Lunch break*                  |
14:00  | [Programmation]                |
15:30  | *Coffee break & questions*     |
15:45  | [Programmation]                |
17:00  | *Wrap-up*                      |


Day 2  | Tuesday February 7th, 2017     |
------ | ------------------------------ |
09:15  | [Computation I]                |
10:30  | *Coffee break*                 |
10:45  | [Computation I]                |
12:00  | *Lunch break*                  |
14:00  | [Visualization I]              |
15:30  | *Coffee break & questions*     |
15:45  | [Visualization I]              |
17:00  | *Wrap-up*                      |


[Introduction]: introduction.md
[Programmation]: http://www.scipy-lectures.org/intro/language/python_language.html
[Computation I]: http://www.scipy-lectures.org/intro/numpy/index.html
[Visualization I]: http://www.labri.fr/perso/nrougier/teaching/matplotlib/matplotlib.html


### Content <a name="beginner-content"></a>

#### Introduction

This [gentle introduction to Python](introduction.md) explains how to install
Python and introduces some very simple concepts related to numerical
expressions and other data types.

#### Programming with Python

[Scipy Lecture
Notes]. This
[lecture](http://www.scipy-lectures.org/intro/language/python_language.html)
does not attempt to be comprehensive and cover every single feature, or even
every commonly used feature. Instead, it introduces many of Python's most
noteworthy features, and will give you a good idea of the language’s flavor and
style.

**See also**:

 * [Dive into Python](http://www.diveintopython3.net)

#### Computation I

[Scipy Lecture Notes]. The primary goal of
this [lesson](http://www.scipy-lectures.org/intro/numpy/index.html) is to
introduce the numpy (numerical python) module which is de facto the standard
module for numerical computing with Python. It is essential for you to become
familiar with this module since it will be used everywhere in the next lessons.

**See also**:

  * [Numpy tutorial](https://github.com/rougier/numpy-tutorial)
  * [100 Numpy exercises](https://github.com/rougier/numpy-100)
  * [Numpy MedKit](http://mentat.za.net/numpy/numpy_advanced_slides/)


#### Scientific visualization I

This [tutorial](https://github.com/rougier/matplotlib-tutorial) gives an
overview of Matplotlib, the core tool for 2D & 2.5D plotting that produces
publication quality figures as well as interactive environments across
platforms.

**See also**:

  * [10 Simple rules for better figures](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003833)
  * [Pyplot tutorial](http://matplotlib.org/users/pyplot_tutorial.html)



## Advanced course <a name="advanced-course"></a>

### Schedule <a name="advanced-schedule"></a>

Day 3  | Monday February 9th, 2017      | 
------ | ------------------------------ |
09:00  | [Computation II]               |
10:30  | *Coffee break*                 |
10:45  | [Computation II]               |
12:00  | *Lunch break*                  |
14:00  | [Version control]              |
15:30  | *Coffee break & questions*     |
15:45  | [Version control]              |
17:00  | *Wrap-up*                      |


Day 4  | Tuesday February 10th, 2017    |
------ | ------------------------------ |
09:15  | [C/Python integration]         |
10:30  | *Coffee break*                 |
10:45  | [C/Python integration]         |
12:00  | *Lunch break*                  |
14:00  | [Visualization II]             |
15:30  | *Coffee break & questions*     |
15:45  | [Visualization II]             |
17:00  | *Wrap-up*                      |


[Computation II]: http://www.scipy-lectures.org/intro/scipy.html
[Version Control]: https://swcarpentry.github.io/git-novice
[C/Python integration]: http://www.scipy-lectures.org/advanced/interfacing_with_c/interfacing_with_c.html
[Visualization II]: http://glumpy.readthedocs.org/en/latest/tutorial/introduction.html)

### Content <a name="advanced-content"></a>

#### Scientific computation II

[Scipy Lecture Notes]. This
[lesson](http://www.scipy-lectures.org/intro/scipy.html) introduces the scipy
package that contains various toolboxes dedicated to common issues in
scientific computing. Its different submodules correspond to different
applications, such as interpolation, integration, optimization, image
processing, statistics, special functions, etc.

**See also**:

  * [Scipy Tutorial](http://docs.scipy.org/doc/scipy/reference/tutorial/)
  * [Numerical Analysis: Python vs Matlab](http://hyperpolyglot.org/numerical-analysis)


#### Version control

[Software Carpentry]. This lesson introduces
[version control using git](https://swcarpentry.github.io/git-novice/). Version
control is the lab notebook of the digital world: it's what professionals use
to keep track of what they’ve done and to collaborate with other people. And it
isn't just for software: books, papers, small data sets, and anything that
changes over time or needs to be shared can and should be stored in a version
control system.

**See also**:

  * [Git Book](https://git-scm.com/book/en/v2)
  * [Git cheat sheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)


#### C/Python integration

[Scipy Lecture Notes]. This
[chapter](http://www.scipy-lectures.org/advanced/interfacing_with_c/interfacing_with_c.html)
contains an introduction to the many different routes for making your native
code (primarily C/C++) available from Python, a process commonly referred to
wrapping. The goal of this chapter is to give you a flavour of what
technologies exist and what their respective merits and shortcomings are, so
that you can select the appropriate one for your specific needs.


#### Scientific visualization II

This [lesson](http://glumpy.readthedocs.org/en/latest/tutorial/introduction.html)
introduces the (modern) OpenGL API through the use of [glumpy] which a python
library for scientific visualization that is both fast, scalable and
beautiful. Glumpy offers an intuitive interface between numpy and modern
OpenGL.

|

----

|

![](PhD-Comics.png)


<!----------------------------- External links ------------------------------->
[Python]:     http://www.python.org
[Numpy]:      http://www.numpy.org
[Scipy]:      http://www.scipy.org
[Pandas]:     http://pandas.pydata.org
[Matplotlib]: http://matplotlib.org
[IPython]:    http://ipython.org
[Jupyter]:    http://jupyter.org
[Git]:        https://git-scm.com
[OpenGL]:     https://www.opengl.org
[Glumpy]:     https://glumpy.github.io
[Bokeh]:      https://bokeh.org
[Cython]:     http://cython.org
[Software Carpentry]:  http://software-carpentry.org
[Scipy Lecture Notes]: http://www.scipy-lectures.org
[From Python to Numpy]: http://www.labri.fr/perso/nrougier/from-python-to-numpy/
[University of Bordeaux]: http://www.u-bordeaux.com
[Python scientific packages]: (https://pypi.python.org/pypi?:action=browse&c=385)
<!---------------------------------------------------------------------------->
