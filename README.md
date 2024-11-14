# Program 2: Gauss-Seidal method

<br>

## Date:

<br>

## Question:

<br>

 Solve the system of equations $$𝟒𝒙 + 𝒚 + 𝒛 = 𝟏; 𝒙 + 𝟑𝒚 + 𝒛 = 𝟐; 𝒙 + 𝒚 + 𝟓𝒛 = 𝟑,$$ using Gauss-Seidal method.

<br>

## Aim:

<br>

 To find the solution of given system of equations by using Gauss-Seidal method.

<br>

## Algorithm:

<br>

  Step 1: Assign $$X_0 = 0, Y_0 = 0, Z_0 = 0$$

<br>

  Step 2: for i = 1 to 9

<br>

  Step 3: Compute $$X = \frac{1}{4} * (1 - Y_0 - Z_0)$$

<br>

  Step 4: Assign $$Y_0 = Y$$

<br>

  Step 5: Compute $$Y = \frac{1}{3} * (2 - X_0 - Z_n)$$

<br>

  Step 6: Assign $$Y_0 = Y$$

<br>

  Step 7: Compute $$Z = \frac{1}{5} * (3 - X_0 - Y_0)$$

<br>

  Step 8: Assign $$Z_0 = Z$$

<br>

  Step 9: Print the value of $$X,Y,Z$$

<br>

## Program:

<br>

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

<br>

## Output:

<br>

The approximate solution of x = 0.0000, y= 0.5000, z=0.5000

<br>

## Result:

<br>

The approximate solution is obtained by using Gauss-Seidal method
