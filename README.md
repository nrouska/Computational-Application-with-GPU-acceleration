# Acceleration with GPU
Project developed by Natalia Rouska, Giorgos Xagorarakis, Ignatios Touvlelios in the Introduction in Computers course.

This repository is for a computational application that performs float32 multiplications on a large square array.

The program executes both on CPU and GPU, thus the results shows the time acceleration that GPU execution offers. 

By using decorator vectorize, the Numba compiler can translate a Python function into a ufunc that operates on NumPy arrays as quickly as if it were written in C.

# Set-up
1. Install Anaconda environment
2. In Anaconda prompt command shell
3. `conda install numba`
4. `conda install cudatoolkit`
