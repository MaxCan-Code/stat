Core functions
==============

⍺   The functions all take an axis as an 
    optional integer left argument. Its default
    value is 1; that is, unlike APL primitives, 
    the functions default to the LEADING axis: 
    the mean of a numerical matrix is the means 
    of its columns.

⍵   For scalar ⍵, the functions return ⍵

The functions are:

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
sum      | total
var      | variance