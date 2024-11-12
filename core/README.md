Core functions
==============

The functions are monadic and operate on the LEADING axis: 
e.g. the mean of a numerical matrix is the means of its columns.

function | result
---------|-------------------
asc      | sort ascending
desc     | sort descending
max      | maximum value
mean     | statistical mean
med      | median value
min      | minimum value
mode     | sample mode
sd       | standard deviation
sqr      | square
sqrt     | square root
sum      | total
var      | variance

Functions max, min, sqr, sqrt and sum are syntacic sugar
and require no tests.