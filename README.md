# N4SID-and-MOESP
These are numerical algorithms for subspace state space system identification. The book that use as reference it will be "Subspace Methods  for System Identification" from Tohru Katayama

# (MOESP algorithm)
Step 1: Compute the LQ decomposition of (6.32).

Step 2: Compute the SVD of (6.39), and let ![](https://latex.codecogs.com/gif.latex?n%20%3A%3D%20dim%20%5CSigma_%7B1%7D) and define the extended observability matrix as

   ![](https://latex.codecogs.com/gif.latex?%5Cmathcal%20O_%7Bk%7D%3D%20U_%7Bk%7D%5CSigma_%7B1%7D%5E%7B1/2%7D)

Step 3: Obtain C and A from (6.41) and (6.42), respectively.

Step 4: Solve (6.44) by the least-squares method to estimate B and D .
