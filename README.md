# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:

### Step 1: 
Import the numpy module to use the built-in functions for calculations

### Step 2: 
Prepare the lists for each linear equations and assign the array in np.sqrt()

### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)

### Step 4: 
End the program

### Step 5: 
Print the value

### PROGRAM:#Program to find the distance between two points.
#Developed by: N.Niharika

#RegisterNumber:21500912

import numpy as np

p1=[10,6]

p2=[4,2]

distance=np.sqrt(((p1[0]-p2[0])**2)+((p1[1]-p2[1])**2))

print("{:.2f}".format(distance))

### OUTPUT:
![output](https://github.com/naramala-niharika/DISTANCE-BETWEEN-TWO-POINTS/blob/main/Screenshot%20(27).png?raw=true)

### RESULT:
Thus distance between two points are executed