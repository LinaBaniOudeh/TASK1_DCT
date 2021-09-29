# TASK1_DCT


Apply DCT to an image
Objective: To visualize the importance of applying DCT to an image by changing the least important coefficients to zero.
Description:
1) Read an image into a matrix
2) Apply 2D-DCT to the matrix
3) Convert the last K coefficients to zero (multiply the last (in zigzag scan) DCT-Coefficients by zeros while all other coefficients are left the same).
4) Apply inverse 2D-DCT transform to the modified DCT coefficients.
5) Display the reconstructed image.
6) Repeat the procedure from 3 to 5 while changing the value of K.
7) Comment on your findings.
