# ParticleMesh
## Introdution
This project is use particle mesh to do N-body simulation, and refer https://github.com/sheroze1123/ppm. Further, we use different density field and use fast fourier transform to solve the poisson equation.
## How to use
This project use the library fftw, http://www.fftw.org/. You need to run Final-project.cpp first and it would output the file(e.g. Data.csv) which include the position of all the particle in different time. And then you can use python file to visualize the result. In the Data.csv case, it records the x,y,z position of two particle, one of them is (4,0,0), and another is (-4,0,0)
