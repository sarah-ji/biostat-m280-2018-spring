*JI, SOO MIN*  

### Overall Grade: 97/100

### Quality of report: 5/5

* Is the homework submitted (git tag time) before deadline?

	Yes. `2018-06-15 11:35:42 -0700` for tag `hw5`. 
	
* Is the final report in a human readable format html? 

	Yes. `html`.

* Is the report prepared as a dynamic document (Jupyter notebook) for better reproducibility?

	Yes. `ipynb`.

* Is the report clear (whole sentences, typos, grammar)? Do readers have a clear idea what's going on and how are results produced by just reading the report? 

    Yes. The report is well written
 
### Correctness and efficiency of solution: 77 / 80

* Q1 (5 / 5 pts) Good job!

* Q2 (8 / 8 pts) Good job!

* Q3 (9 / 12 pts)  
       * No comment on why it is not easy to maximize the Q function(-3 pts )
       Maximizing $Q$ is not trivial since $\alpha_j$ are intertwined in the $ln(\gamma(|\alpha|))$ 

* Q4 (15 / 15 pts) Good job!

* Q5, Q6 (30 / 30 pts)

     * Pre-compute sufficient statistics `Sjk` and `rk` before MM loop. (5 / 5 pts)

     * code Newton loop correctly (5 / 5 pts)

     * Update alpha correctly. (5 / 5pts). 

     * MM should get similar results to Newton's method. May be slower. (15 / 15 pts)

* Q7 (10 / 10 pts)


### Usage of Git: 5/5

* Are branches (`master` and `develop`) correctly set up? Is the hw submission put into the `master` branch?

	Yes.
	
* Are there enough commits? Are commit messages clear? 
	
	Yes
	
* Is the hw5 submission tagged?

	Yes.

* Are the folders (`hw1`, `hw2`, ...) created correctly? 

	Yes.

* Do not put a lot auxillary files into version control.  

	Yes.

### Reproducibility: 2/2

* Are the materials (files and instructions) submitted to the `master` branch sufficient for reproducing all the results?

	Yes.
	
* If necessary, are there clear instructions, either in report or in a separate file, how to reproduce the results?  

	Not applicable for hw5.

### Julia code style: 8/8

* Rule (4): 4 spaces for indenting. 

* Rule (6): Never place more than 80 characters on a line. 

* Rule (7): Always include a single space after a comma. 

* Rule (8):  Never insert a space before a comma.

* Rule (9): Always insert a single space before and after an operator, except for the `^` and `:` operators, which never have spaces around them. 

* Rule (12): When naming variables or functions, use short lowercase names if possible.

* Rule (13): If a variable or function name is too long to be read in all lowercase, insert underscores at word boundaries.

* Rule (16): When naming constants, use all caps.
