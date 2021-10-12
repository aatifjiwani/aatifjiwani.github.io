---
name: NumS - Open Source Contribution
img: ../imgs/nums.jpg
img_size: 200px
links:
 - name: Report
   value: ../pdfs/nums.pdf
 - name: Code
   value: https://github.com/nums-project/nums
   last: true
ordering: 1
---
NumS is a Python library that translates n-dimensional matrix operations across a distributed network of computers by using Ray as a backend for scheduling tasks, and managing the memory and resources of a node cluster. For my final project and as an open source contribution, I implemented an algorithm (based on [Bientenisi et al.](https://www.cs.utexas.edu/users/flame/pubs/siam_spd.pdf)) that performs a matrix inversion on upper-triangular matrices, specifically the R matrix from QR factorization. We can use this algorithm for least squares regression on extremely large data with any number of features, and subsequently show that this algorithm performs better than naive matrix inversion.  