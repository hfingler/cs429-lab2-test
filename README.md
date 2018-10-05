# cs429-lab2-test


To use this:

1. Copy all files to your assignment lab, note that this will overwrite the Makefile if you changed it. In this case, copy the grade rule to it.
2. Run "make grade", to build the C file, this will link to your assembly and C files to the grading script
3. Run "python grade.py". This will run all the tests that are in the "tests" array in the python file.


As you finish a function and you want to test it, write the tests to the tests array in the python file and uncomment the function that tests it in grade.c. Then recompile by doing: "make clean ; make".

If you find any errors (and you probably will, post on Piazza and I'll fix it ASAP).