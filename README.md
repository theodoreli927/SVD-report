# Singular Value Decomposition Analysis

Here is my detailed mathematical report on Singular Value Decomposition. Here you will find my report in pdf format, and a jpg and .mat file used in my reproducible python code within my report. I will begin to give a brief overview of each section of this report.

First I begin with a introduction and explanation of SVD followed by a proof of how any matrix decomposed using SVD can be rewritten as a sum of rank 1 matrices.

Now that I've introduced SVD and its properties, next I analyzed the best rank-\(k\) approximation of a matrix \(A\), and proved how the 2-norm of \(A - A_k\) would be equal to \(\sigma_{k+1}\).

Next, after examining best rank-\(k\) approximation of a matrix \(A\), I delve into analyzing the left and right singular values of \(A\)

Now that I examined SVD and all it's various components, I computed the SVD of a specified matrix and found its rank-1 approximation step-by-step.

This concluded the theory section, next I began a practical real-world analysis on SVD using Python to deconstruct an image into 3 channels of Red, Green, Blue and computed their best rank-k approximations. After computing their errors I outputted all values of k-approximations to visualize their effect in approximating a image:


![Visualization of Best Rank-k Approximations]("C:\Users\theod\Downloads\CMDA_3605\k_approx_images.png")

Finally, I used SVD to also reconstruct a image:

![Reconstructed Image 1]("C:\Users\theod\Downloads\CMDA_3605\reconstructed_images.png")
![Reconstructed Image 2]("C:\Users\theod\Downloads\CMDA_3605\reconstructed_images_2.png")
![Reconstructed Image 3]("C:\Users\theod\Downloads\CMDA_3605\reconstructed_images_3.png")



