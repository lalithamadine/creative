1.JavaScript Date objects can only be instantiated by calling JavaScript Date as a constructor:
calling it as a regular function (i.e. without the new operator) will return a string rather than a Date object; 
unlike other JavaScript object types, JavaScript Date objects have no literal syntax.
var date= new Date();
---------
2.The radial-gradient() function sets a radial gradient as the background image.
A radial gradient is defined by its center.
To create a radial gradient you must define at least two color stops.
----------
3.Thus,you can access each property by entering the name of the property as a string into this array. 
Such an array associates each key with a value (in this case the key Home is associated with the value normal).
----------
4.calculating a date interval such as days, weeks, or months between two known dates is not as easy because 
you can't just add Date objects together. In order to use a Date object in any sort of calculation, 
we must first retrieve the Date's internal millisecond value, which is stored as a large integer. 
The function to do that is Date.getTime(). Once both Dates have been converted, subtracting the later one
from the earlier one returns the difference in milliseconds. The desired interval can then be determined by 
dividing that number by the corresponding number of milliseconds. For instance, to obtain the number of days for 
a given number of milliseconds, we would divide by 86,400,000, the number of milliseconds in a day (1000 x 60 seconds x 60 minutes
x 24 hours):
-----------
5.forEach accepts a callback function and, optionally, a value to use as this when calling that callback (not used above).
The callback is called for each entry in the array, in order, skipping non-existent entries in sparse arrays. Although I only 
used one argument above, the callback is called with three: The value of each entry, the index of that entry, and a reference 
to the array you're iterating over(in case your function doesn't already have it handy).
-----------
5.
map calls a provided callback function once for each element in an array, in order, and constructs a new array 
from the results. callback is invoked only for indexes of the array which have assigned values, including undefined. 
It is not called for missing elements of the array (that is, indexes that have never been set, which have been deleted or
which have never been assigned a value).
