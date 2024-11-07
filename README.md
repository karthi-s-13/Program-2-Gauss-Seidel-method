# Program 2: Gauss-Seidal method

## Question:

Solve the system of equations $$𝟒𝒙 + 𝒚 + 𝒛 = 𝟏; 𝒙 + 𝟑𝒚 + 𝒛 = 𝟐; 𝒙 + 𝒚 + 𝟓𝒛 = 𝟑,$$ using
Gauss-Seidal method.

## Aim:

To find the solution of given system of equations by using Gauss-Seidal method.

## Algorithm:

Step 1: Assign $$X_0 = 0, Y_0 = 0, Z_0 = 0$$

Step 2: for i = 1 to 9

Step 3: Compute $$X = \frac{1}{4} * (1 - Y_0 - Z_0)$$

Step 4: Assign $$Y_0 = Y$$

Step 5: Compute $$Y = \frac{1}{3} * (2 - X_0 - Z_n)$$

Step 6: Assign $$Y_0 = Y$$

Step 7: Compute $$Z = \frac{1}{5} * (3 - X_0 - Y_0)$$

Step 8: Assign $$Z_0 = Z$$

Step 9: Print the value of $$X,Y,Z$$

## Program:
```
x0=0; y0=0; z0=0
for i in range (1,10):
 x=1/4*(1-y0-z0)
 x0=x
 y=1/3*(2-x0-z0)
 y0=y
 z=1/5*(3-x0-y0)
 z0=z
print ("The approximate solution of x = %.4f, y= %.4f, z=%.4f"% (x, y,
z))
```

## Output:

The approximate solution of x = 0.0000, y= 0.5000, z=0.5000

## Result:

The approximate solution is obtained by using Gauss-Seidal method
