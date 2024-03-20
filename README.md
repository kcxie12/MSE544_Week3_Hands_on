# MSE544_Week3_Hands_on

## Hands-on 3: Parallelization in Matrix Multiplication.

Authors: Ting Cao & [Ziyu Zhang](https://github.com/Ilxxll)

### Table of Content

- [Background & Goals](#background)
- [Performance Analysis of Matrix Multiplication with Varying Numbers of Cores.](#task)
- [Submission](#submission)

## Background & Goals for this week's hands-on <a name="background"></a>

#### Matrix multiplication & parallelization

Matrix multiplication is a fundamental operation in various scientific and engineering fields, such as machine learning, data analysis, physics, and computer graphics. As the size of matrices increases, the time required for matrix multiplication also increases, making it a computationally expensive operation.

To address this issue, parallelization has been widely adopted to accelerate matrix multiplication. Parallelization involves breaking down a task into smaller sub-tasks that can be executed simultaneously on multiple computing units, such as cores in a processor or nodes in a high-performance computing (HPC) cluster. By utilizing multiple computing units in parallel, the total time required to complete the task can be significantly reduced.

#### Goals for this week's Hands-on

The aim of this homework is to gain an understanding of program efficiency and performance under different core numbers, and to develop skills in using data to evaluate and compare program performance. By completing this practical task, students will learn how to analyze the performance of the program with varying numbers of cores, and identify the optimal core number for this particular matrix size on a high-performance computing cluster.

## Performance Analysis of Matrix Multiplication with Varying Numbers of Cores. <a name="task"></a>

1. Please download: `Hands_on.zip` from Canvas. Unzip it in your local computer, and read the scripts in it.

2. Open the provided script `matmul_3.py` in a text editor and change the `SIZE` parameter to 5000.

3. Upload `matmul_3.py` and `script` to Hyak.

4. Open the `script` using `vi` command and modify the `--ntasks-per-node` parameter by changing the value of `n` to 1, 2, 4, 8, and 16, respectively.

5. Save the job script and **submit the job as a batch job**.

6. Wait for the job to complete execution.

7. Once the job is completed, check the output file generated by the job to record the time taken by the matrix multiplication for each number of cores.

8. Repeat steps 4 to 7 for each value of `n`.

9. After recording the times for each value of `n`, analyze the data to evaluate the performance of the program with different numbers of cores.

10. Based on the analysis, identify the optimal number of cores for this particular matrix size on the high-performance computing cluster.


## Submission. <a name="submission"></a>

Submit a text file or a block of text containing the recorded times for each value of "n" to complete the homework assignment.
