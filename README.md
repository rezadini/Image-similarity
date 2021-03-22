Image-similarity
===============

Different programs for calculating percentage similarity of two images

*	hashes.py - Calculate Image similarity based on phash
*	drawMatches.py - mapping of similar points of 2 images
*	knn.py - iterate through all images in given folder to find similar images (sim % > 80) and delete them 
*	knnsingle.py - mapping similar points in 2 images using knn

Usage:
*	python < hashes.py / drawMatches.py / knnsingle.py > < img1 > < img2 >
*	python knn.py < dir >

Hi, is it for Python 2 03 3?
I got the following error message when i run the program.
Could you please help? Thanks

Python 3.8.5 (default, Sep  3 2020, 21:29:08) [MSC v.1916 64 bit (AMD64)]
Type "copyright", "credits" or "license" for more information.

IPython 7.19.0 -- An enhanced Interactive Python.

runfile('D:/Image-similarity-master/hashes.py', wdir='D:/Image-similarity-master')
  File "D:\Image-similarity-master\hashes.py", line 12
    return reduce(lambda x, (y, z): x | (z << y),
                            ^
SyntaxError: invalid syntax
