# Course Description
* Course Name: ***Introduction to Natural Language Processing***
* Instructor: ***Dragomir R. Radev***
* University: ***University of Michigan***
* Suggested Readings
    * Daniel Jurafsky and James Martin - [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/)
    * Bird et al - NLTK. Check the www.nltk.org site.
   
# Resources
### Related courses
1. Natural Langugage Processing
2. Natural Langugage Processing
3. [CS224d: Deep Learning for Natural Language Processing](http://cs224d.stanford.edu/)


# Required environment
1. Python (== 2.7)
2. NLTK (==3.0)
3. NumPy (>= 1.6.1)
4. SciPy (>= 0.9)
5. sklearn (==0.15.2) - important!
### Create a virtual environment for this course
1. Create a vitural environment
   ```
   create --name introNLP nltk=3.0 numpy scipy scikit-learn=0.15.2 nltk=3.0 numpy scipy scikit-learn=0.15.2
   ```
       package                    |            build
    ---------------------------|-----------------
    mkl-11.3.3                 |                1       110.0 MB
    vs2008_runtime-9.00.30729.1|                2         1.0 MB
    python-2.7.12              |                0        23.5 MB
    nose-1.3.7                 |           py27_1         247 KB
    numpy-1.9.3                |           py27_3         2.8 MB
    pyyaml-3.11                |           py27_4         169 KB
    setuptools-23.0.0          |           py27_0         688 KB
    nltk-3.0.5                 |           py27_0         1.6 MB
    pip-8.1.2                  |           py27_0         1.5 MB
    scipy-0.16.0               |       np19py27_0        83.7 MB
    scikit-learn-0.15.2        |       np19py27_0         3.3 MB
    ------------------------------------------------------------
                                           Total:       228.4 MB
2. activate this enviroment
   '''
   source activate introNLP
   '''
   
* [Install NLTK from official site](http://www.nltk.org/install.html)
* [Windows7 平台下Python+NLTK环境搭建](http://blog.csdn.net/u010784534/article/details/48847697)

   ```
   import numpy
   numpy.version.version
   ```

* [How to Check Version of Scipy](http://stackoverflow.com/questions/21385196/how-to-check-the-version-of-scipy)
   ```
   import scipy
   scipy.__version__
   ```


* [Install Scikit-Learn](http://scikit-learn.org/stable/install.html)
