Documentation of the test instances

All instances used in the paper

  A Penalty Branch-and-Bound Method for Mixed-Binary Linear Complementarity Problems

by Marianna De Santis, Sven de Vries, Martin Schmidt, Lukas Winkel

can be found in these directories. The instances used in the
preliminary tests we refer to in the appendix can be found in the
folder

  Testset_Preliminary.

The instances used in the tests for the enhancements and the first
benchmark test can be found in the directories

  Testset_Enhancements_<X>

Here, the <X> refers to the degree of feasibility as defined in the
appendix. The instances for the second benchmark test can be found in
the directories

  Testset_Benchmark_<X>.

Again, the <X> refers to the degree of feasibility as defined in the
appendix.

All files with test instances contain the data of the instance
line-wise in the following format:

- Emphasis parameter alpha (not used but instead set to 0.5)
- Instance size n
- Density of matrix M
- Highest possible value of eigenvalues of M
- Highest possible value of entries in M
- Ratio of integer variables to continuous variables
- Degree of feasibility as described in the appendix
- Number of integer variables
- A feasible point z with every entry in a new line
- Vector q with every entry in a new line
- Matrix M with every entry in a new line (left to right, top to bottom)
