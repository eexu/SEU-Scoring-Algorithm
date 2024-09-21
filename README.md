# SEU-Scoring-Algorithm

This page is created to explain the Standardized Results Algorithm of Southeast University.

1. Standardized Results.
   
Assuming the average score of a course is $X$ and your score is $Y$, the Standardized Result is $(Y-X+80)$, which calculates the increment of your score to the average score and adds 80.

2. Weighted Standardise Results.

Weight the Standatdised Results with credits.

$$
N=\frac{\sum C_i^* N_i}{\sum C_i}
$$

where $Ci$ is the credit of the $i$th course and $N_i$ is its correspongidng Standardised Results.

Reference:
[1] [Southeast Scoring Algorithm](https://seugs.seu.edu.cn/_upload/article/files/1a/d8/d8453cc24283b3b250a2756eed1f/db5ce9f9-2dde-4775-97a3-efd64c94ecd5.pdf)
