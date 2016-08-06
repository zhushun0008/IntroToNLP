# Course Description
* Course Name: ***Introduction to Natural Language Processing***
* Instructor: [***Dragomir R. Radev***](http://web.eecs.umich.edu/~radev/)
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
5. sklearn (==0.15.2) - ***important!***

### Installation Reference
* [Install NLTK from official site](http://www.nltk.org/install.html)
* [Windows7 平台下Python+NLTK环境搭建](http://blog.csdn.net/u010784534/article/details/48847697)
* [Install Scikit-Learn](http://scikit-learn.org/stable/install.html)
* [Installing specific version of packages from discussion forum of this course](https://www.coursera.org/threads/upiUoEHVEeaXnBKVQldqyw)

### Create a virtual environment for this course
1. Create a vitural environment

   ```
   create --name introNLP nltk=3.0 numpy scipy scikit-learn=0.15.2 nltk=3.0 numpy scipy scikit-learn=0.15.2
   ```
   
2. Activate this enviroment

   ```
   activate introNLP
   ```
   
3. Check versions for packages
   * [Check version for NLTK and Scikit-Learn](https://codedump.io/share/trqm6WVMb8z2/1/how-to-check-which-version-of-nltk-scikit-learn-installed)
   * [How to Check Version of Scipy](http://stackoverflow.com/questions/21385196/how-to-check-the-version-of-scipy)

   ```
   import nltk  
   nltk.__version__ 
   
   import numpy
   numpy.version.version
   
   import scipy
   scipy.__version__
   
   import sklearn
   sklearn.__version__
   ```

4. Deactivate for current virtual enviroment
   ```
   deactivate
   ```

