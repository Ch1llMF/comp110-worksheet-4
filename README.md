# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a 
     |  A  |  B  |  C  |  Not C  |  A and B and not C  |
     |-----|-----|-----|---------|---------------------|
     |  0  |  0  |  0  |    1    |           0         |
     |  0  |  0  |  1  |    0    |           0         |
     |  0  |  1  |  0  |    1    |           0         |
     |  0  |  1  |  1  |    0    |           0         |
     |  1  |  0  |  0  |    1    |           0         |
     |  1  |  0  |  1  |    0    |           0         |
     |  1  |  1  |  0  |    1    |           1         |
     |  1  |  1  |  1  |    0    |           0         |

### b
     |  A  |  B  |  C  |  B and not C  |  A and not (B and not C)  |
     |-----|-----|-----|---------------|---------------------------|
     |  0  |  0  |  0  |       0       |             0             |
     |  0  |  0  |  1  |       0       |             0             |
     |  0  |  1  |  0  |       1       |             0             |
     |  0  |  1  |  1  |       0       |             0             |
     |  1  |  0  |  0  |       0       |             1             |
     |  1  |  0  |  1  |       0       |             1             |
     |  1  |  1  |  0  |       1       |             0             |
     |  1  |  1  |  1  |       0       |             1             |
### c
     |  A  |  B  |  C  |  A or not B  |  A or C  |  (A or not B) and (A or C)  |
     |-----|-----|-----|--------------|----------|-----------------------------|
     |  0  |  0  |  0  |       1      |     0    |              0              |
     |  0  |  0  |  1  |       1      |     1    |              1              |
     |  0  |  1  |  0  |       0      |     0    |              0              |
     |  0  |  1  |  1  |       0      |     1    |              0              |
     |  1  |  0  |  0  |       1      |     1    |              1              |
     |  1  |  0  |  1  |       1      |     1    |              1              |
     |  1  |  1  |  0  |       1      |     1    |              1              |
     |  1  |  1  |  1  |       1      |     1    |              1              |
### d
     |  A  |  B  |  C  |  D  |  B or Not C  |  Not A and D  |  A and Not (B or Not C) and (Not A and D)  |  
     |-----|-----|-----|-----|--------------|---------------|--------------------------------------------|
     |  0  |  0  |  0  |  0  |       1      |       0       |                    0                       |
     |  0  |  0  |  0  |  1  |       1      |       1       |                    0                       |
     |  0  |  0  |  1  |  0  |       0      |       0       |                    0                       |
     |  0  |  0  |  1  |  1  |       0      |       1       |                    0                       |
     |  0  |  1  |  0  |  0  |       1      |       0       |                    0                       |
     |  0  |  1  |  0  |  1  |       1      |       1       |                    0                       |
     |  0  |  1  |  1  |  0  |       1      |       0       |                    0                       |
     |  0  |  1  |  1  |  1  |       1      |       1       |                    0                       |
     |  1  |  0  |  0  |  0  |       1      |       0       |                    0                       |
     |  1  |  0  |  0  |  1  |       1      |       0       |                    0                       |
     |  1  |  0  |  1  |  0  |       0      |       0       |                    0                       |
     |  1  |  0  |  1  |  1  |       0      |       0       |                    0                       |
     |  1  |  1  |  0  |  0  |       1      |       0       |                    0                       |
     |  1  |  1  |  0  |  1  |       1      |       0       |                    0                       |
     |  1  |  1  |  1  |  0  |       1      |       0       |                    0                       |
     |  1  |  1  |  1  |  1  |       1      |       0       |                    0                       |
## Question 2

### a
See A and B and Not C.PNG
### b
See A and Not(B and Not C).PNG
### c
See (A or Not B) and (A or C).PNG
### d
See A and Not (B or Not C) and(Not A and D).PNG
## Question 3

### a
  |  A  |  B  |  Not (A or B)  |  Not A and Not B  |
  |-----|-----|----------------|-------------------|
  |  0  |  0  |       1        |         1         |
  |  0  |  1  |       0        |         0         |
  |  1  |  0  |       0        |         0         |
  |  1  |  1  |       0        |         0         |
### b
  |  A  |  B  |  Not (A and B)  |  Not A or Not B  |
  |-----|-----|-----------------|------------------|
  |  0  |  0  |        1        |         1        |
  |  0  |  1  |        1        |         1        |
  |  1  |  0  |        1        |         1        |
  |  1  |  1  |        0        |         0        |
### c
  |  A  |  B  |  C  |  A and B  |  A and C  |  (A and B) or (A and C)  |  B or C  |  A and (B or C)  |
  |-----|-----|-----|-----------|-----------|--------------------------|----------|------------------|
  |  0  |  0  |  0  |     0     |     0     |             0            |    0     |         0        |
  |  0  |  0  |  1  |     0     |     0     |             0            |    1     |         0        |
  |  0  |  1  |  0  |     0     |     0     |             0            |    0     |         0        |
  |  0  |  1  |  1  |     0     |     0     |             0            |    1     |         0        |
  |  1  |  0  |  0  |     0     |     0     |             0            |    0     |         0        |
  |  1  |  0  |  1  |     0     |     1     |             1            |    1     |         1        |
  |  1  |  1  |  0  |     1     |     0     |             1            |    1     |         1        |
  |  1  |  1  |  1  |     1     |     1     |             1            |    1     |         1        |
### d
  |  A  |  B  |  C  |  A or B  |  A or C  |  (A or B) and (A or C)  |  B and C  |  A or (B and C)  |
  |-----|-----|-----|----------|----------|-------------------------|-----------|------------------|
  |  0  |  0  |  0  |    0     |    0     |            0            |     0     |        0         |
  |  0  |  0  |  1  |    0     |    1     |            0            |     0     |        0         |
  |  0  |  1  |  0  |    1     |    0     |            0            |     0     |        0         |
  |  0  |  1  |  1  |    1     |    1     |            1            |     1     |        1         |
  |  1  |  0  |  0  |    1     |    1     |            1            |     0     |        1         |
  |  1  |  0  |  1  |    1     |    1     |            1            |     0     |        1         |
  |  1  |  1  |  0  |    1     |    1     |            1            |     0     |        1         |
  |  1  |  1  |  1  |    1     |    1     |            1            |     1     |        1         |
## Question 4

### a
  |  A.txt  |  B.txt  |  Not (A.txt and B.txt)  |  Not A.txt or Not B.txt  |  
  |---------|---------|-------------------------|--------------------------|  
  |     0   |    0    |            1            |             1            |
  |     0   |    1    |            1            |             1            |
  |     1   |    0    |            1            |             1            |
  |     1   |    1    |            0            |             0            |
### b
|  Int  |  Float  |  X > 7  |  Int and x > 7  |  Float and x > 7 |  (Int and x > 7) or (Float and x > 7)  |
|-------|---------|---------|-----------------|------------------|----------------------------------------|
|   0   |    0    |    0    |        0        |         0        |                    0                   |
|   0   |    0    |    1    |        0        |         0        |                    0                   |
|   0   |    1    |    0    |        0        |         0        |                    0                   |
|   0   |    1    |    1    |        0        |         1        |                    1                   |
|   1   |    0    |    0    |        0        |         0        |                    0                   |
|   1   |    0    |    1    |        1        |         0        |                    1                   |
|   1   |    1    |    0    |        0        |         0        |                    0                   |
|   1   |    1    |    1    |        1        |         1        |                    1                   |

|  Int or Float  |  (Int or Float) and x > 7  |
|----------------|----------------------------|
|        0       |             0              |
|        0       |             0              |
|        1       |             0              |
|        1       |             1              |
|        1       |             0              |
|        1       |             1              |
|        1       |             0              |
|        1       |             1              |
### c
|  x = 0  |  y = 0  |  x = 0 and y = 0  |
|---------|---------|-------------------|
|    0    |    0    |         0         |
|    0    |    1    |         0         |
|    1    |    0    |         0         |
|    1    |    1    |         1         |

The second bit of code does nothing unless both x and y = 0
### d
|  x > 10  |  x > 0  |  y > 0  |  x > 0 and y > 0  |  x > 10 or (x > 0 and y > 0)  |
|----------|---------|---------|-------------------|-------------------------------|
|     0    |    0    |    0    |         0         |               0               |
|     0    |    0    |    1    |         0         |               0               |
|     0    |    1    |    0    |         0         |               0               |
|     0    |    1    |    1    |         1         |               1               |
|     1    |    0    |    0    |         0         |               1               |
|     1    |    0    |    1    |         0         |               1               |
|     1    |    1    |    0    |         0         |               1               |
|     1    |    1    |    1    |         1         |               1               |


|  x > 10 or y > 0  |  x > 0 and (x > 10 or y > 0)  |
|-------------------|-------------------------------|
|         0         |               0               |
|         1         |               0               |
|         0         |               0               |
|         1         |               1               |
|         1         |               0               |
|         1         |               0               |
|         1         |               1               |
|         1         |               1               |

The second code was would not equal the same results as the first code.

