# Statistics and Methods in Research
Each analysis will have a capacity (how many things it can measure), intent (what it measures), and limitations (the required assumptions)
## Dictionary
* Parametric: require the data to be "normally distributed"
* Non-parametric: does not require data to be normal. Good for skews.
* Power: the chance that a test will detect a true significance
* Ordinal Data: Rankings, or a scale of 0-10

## Statistical Concepts
### How do you know if your data is normally distributed?
You will have to gather "enough" data to determine. This is proportional to the sample size. Other clues will be the anticipated shape of the data. If its not roughly bell-shaped, its likely not normal.

## Statistical Analyses
### Kruskal-Wallis test
* 
### Mann-Whitney U Test
* Non-parametric
* Ranks all results along 1 scale
* Checks if one group ranks lower/higher than the other
* Compares only 2 groups at a time
* Gets a "U Statistic" which is compared to a pre-determined p-value
* shittier power
### ANOVA
* Like an action potential. If crosses the "threshold of significance," then POST-HOC tests are run to see where the deviation originates from
* A magnitude of significance among the analyzed groups.
* Cannot determine which of the groups contains the deviation.
* Assesses the deviation of 3+ means from each other (are any of the groups statistically significant from each other?)
* Must assume that:
(1) each result is not influenced by any other result
(2) that each dependent variable has a normal distribution
(3) Homogeneity of Variance (the range of the distribution is roughly equal for all groups).
### T-Test
* Compares pairs of results
* Considered a POST-HOC
* great power
### Tukey's Honestly Significant Difference (HSD)
* There is increased risk of a false positive error detected each time you run a test, and the risk accumulates over the entire project
* "Honestly" implies the increase in rigor for the Type I error detection risk with multiple tests. It increases the threshold for "significance."
### Chi-Square
## Post-Hoc Tests
Tests that triangulate the origin of variance/deviation/significance after a positive result from a general test
