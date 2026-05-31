Name: Ritesh DP
Register No: 212225040339

# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1:
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4:
End the program

## Program:

# Given matrix
matrix = [[1, 2, 3],
          [3, 6, 9]]

# Check if second row is a multiple of first row
if matrix[1][0] == 3 * matrix[0][0] and    matrix[1][1] == 3 * matrix[0][1] and    matrix[1][2] == 3 * matrix[0][2]:
    rank = 1
else:
    rank = 2

print(rank)
## Output:

<img width="1287" height="307" alt="image" src="https://github.com/user-attachments/assets/a9b71101-d410-470d-aa9c-e99c8c024ead" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

