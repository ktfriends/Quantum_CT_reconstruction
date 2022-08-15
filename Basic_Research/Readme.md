# Preliminary Study for Quantum Optimization Algorithms
```
Jennifer Kim
Cardozo High School
Queens, NY, USA.
jjjenniferkim07@gmail.com
```

## Files summary
```
1. ax_b.ipynb
Problem: Given ax = b and find x
QUBO model: (ax-b)^2 - b^2
Minimum energy: -b^2

Range of x            Qubit representation
0 <= x <= 1            x = q1
0 <= x <= 3            x = q1 + 2q2
0 <= x <= 7            x = q1 + 2q2 + 4q3
0 <= x <= 15           x = q1 + 2q2 + 4q3 + 8q4
```
```
2. Ax_b_Translation.ipynb
Problem: Given ax = b and find x
QUBO model: (ax-b)^2 - b^2
Minimum energy: -b^2

Range of x            Qubit representation
5 <= x <= 8            x = q1 + 2q2 + 5
7 <= x <= 14           x = q1 + 2q2 + 4q3 + 7
-10 <= x <= -7         x = q1 + 2q2 - 10
```
```
3. Linear_System_2by2.ipynb
Problem: Given two line equations: a)a1*x + b1*y = c1, b)a2*x + b2*y = c2 and find the intersection point
QUBO model: (a1*x + b1*y - c1)^2 + (a2*x + b2*y - c2)^2 - (c1^2 + c2^2)
Minimum energy: -(c1^2 + c2^2)
```
```
4. CT_2by2_01_03.ipynb
Problem: Quantum optimization algorithm for CT image reconstruction
Test image information: 2 by 2 image, each pixel has random integer
1. CT image with qubit variable
2. Calculate a sinogram by applying Radon transform to the CT image
3. Opmization the sinogram with qubit variable to the sinogram obtained by the experiment
```



