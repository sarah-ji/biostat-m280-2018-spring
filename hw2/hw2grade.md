*JI, SOO MIN*

### Overall Grade: 98/100

### Quality of report: 10/10

* Is the homework submitted (git tag time) before deadline? 

	Yes. `2018-05-11 14:45:21 -0700`. 

* Is the final report in a human readable format html?  

	Yes,  `html`.

* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?

	Yes, `ipynb`.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report?

	Very clear report
 
### Correctness and efficiency of solution: 48/50 

* Q1 (25/25 pts)

    1, 3) (15/15 pts)
    
    **Efficiency(11/11pts)**
    Dr. Zhou's implementation for `r = 20` has memory estimate 7.12 MB and allocs estimate 10, yours is `33 allocations: 7.972 MiB, 0.17% gc time`. Pretty good! 
    -  Dr. Zhou's implement uses half of the memory in pre-allocation. You may want to check Dr. Zhou's implement

     **Correctness(4/4 pts)**
    
    4, 5) (5/5pts) Good job!
    2, 6) (5/5pts) Good job!


* Q2 (23/25 pts)

    1) (5/5pts) 
    2) (20/20 pts)
    **Algorithm(7/7pts)**
    **Efficiency(5/7pts)**
    Dr. Zhou's implementation has memory allocation 1.34KB, yours is 4.17 KB. Pretty good! Some suggestions:
    - Use `BLAS.syrk!()` to reduce memory allocation in `σ1^2 * Z * Z.' + σ0^2 * I` and save all symmetric matrix in form symmetric  (-1 pts)
    - The extra memory allocation caused by transpose can be avoid by using Blas functions in  `Z' * y`. (-1 pts)
    **Correctness(6/6pts)**

    **Others**
    You can check the input to make the function more stable for wrong input.
    
### Usage of Git: 10/10

* Are branches (`master` and `develop`) correctly set up? Is the hw submission put into the `master` branch?

	Yes.

* Are there enough commits? Are commit messages clear? 

	Yes

* Is the hw2 submission tagged? 

	Yes

* Are the folders (`hw1`, `hw2`, ...) created correctly?

	Yes.	

* Do not put a lot auxillary files into version control.  

	Yes.
		

### Reproducibility: 10/10

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results? 

	Yes

* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

	Not applicable for hw2.

### Julia code style: 20/20

* Rule (4): 4 spaces for indenting.

* Rule (6): Never place more than 80 characters on a line.

* Rule (7): Always include a single space after a comma. 

* Rule (8):  Never insert a space before a comma.

* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them. 

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.
