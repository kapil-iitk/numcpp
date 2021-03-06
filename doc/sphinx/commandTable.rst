*************************************
NumCpp / Numpy / Matlab Command Table
*************************************

.. highlight:: c++

.. contents::
   :depth: 1
   :local:


Array Size Properties
=================================

==============  ==========================  =========================  =================================
Matlab          Numpy                       Numcpp                     Description
==============  ==========================  =========================  =================================
ndims(x)        ndim(a) or a.ndim           ndims(a) or a.ndims        number of dimensions (rank) of a
size(x)         shape(a) or a.shape         shape(a) or a.shape()      vector of  
size(x,d)       shape(a,d) or a.shaped[d]   shape(a,d) or a.shape(d)   number of elements along axis d
length(a(:))    a.size                      size(a) or a.size()        total number of elements of a
==============  ==========================  =========================  =================================


Matrix Manipulation
=====================

==============  ==========================  =============================  =====================================================
Matlab          Numpy                       Numcpp                         Description
==============  ==========================  =============================  =====================================================
fliplr(a)       fliplr(a)                   fliplr(a) or fliplr\_(a)        Flip left-right  (use fliplr\_ for inplace)
flipud(a)       flipud(a)                   flipud(a) or flipud\_(a)        Flip up-down  (use flipud\_ for inplace)
flipdim(a,d)    flipdim(a,d)                flipdim(a,d) or flipdim_(a,d)  Flip elements along axis d (use flipdim\_ for inplace)

rot90(a)        rot90(a)                    rotl90(a)                      Rotate 90 degrees
==============  ==========================  =============================  =====================================================
