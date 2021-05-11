# cnsrFileFormatSpecification
**every line in cnsr file is as follows:**

**start_time - end_time ; type**

-important! the file should be ordered by starting times! 

-white-space characters are ignored-

# keys:
start time 
-
the starting timestamp

marks the start of the segment

**example**: 00:05:21,123 (miliseconds)

end_time 
-
the ending timestamp

marks the end of the segment

**example**: 00:05:55,124 (miliseconds)

type
-
can be one of these:

1 - Violence

2 - Verbal abuse

3 - Nudity

4 - alcohol and drug consumption

# final example:
a proper line should look like this: 

00:05:21,123 - 00:05:55,124 ; 2
