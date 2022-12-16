[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Lab+2)](https://git.io/typing-svg)
### Info for files and directores: ###

* Data directory        - values from two matrices and result values

* Stats directory       - directory with satistics files

* PP_lab2             - contains cpp code

----

### Task: Modify the program from l/w №1 for parallel work using OpenMP technology. ###

----

Work done in release x64:

![](/Stats/image.png) 

Work done in release x64 with 6 threads, because my cpu has 6 logical cores:

![](/Stats/omp_6_threads.jpg) 

The difference in the number of threads:

![](/Stats/number_of_threads.jpg)

----

### Conclusion: With the help of OpenMP technology, two square matrices of 1000 by 1000 were first created, and then the result of multiplying these two matrices was calculated, and the time spent on multiplication was also measured. The most efficient was to use 6 threads (time ≈0.807 sec). ###
