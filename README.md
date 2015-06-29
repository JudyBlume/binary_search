# binary_search

Binary search algorithm search for the required value using half-interval search method. And it only works on the sorted data. This is divide and conquer algorithm and has logarithmic complexity.

It start with comparing the search variable with the middle element.
Function:

function binarysearch(sorted_Array, search_variable)

If search_variable==middle element
then
middle Position is returned.
else
if search_variable<middle element
binarysearch(sorted_Array[1-sorted_Array.length/2],search_variable)
if search_variable>middle element
binarysearch(sorted_Array[sorted_Array.length/2+1-sorted_Array.length],search_variable)

<a href="http://www.chicagocomputerclasses.com/excel-classes/">Here</a> is the full file to know more about this code.

Maya Angelou -Assistant Finance Manager at Raho Sol. 
