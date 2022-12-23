# Computational-physics-projects
This is a list of computational projects I have done during my computational physics module course in UoM


## First Project: Spreading law by Droplet

The spreading of droplet on a flat surface can give an empirical formula between the speed on which the droplet makes contact and the angle it makes. This relation is called the spreading law. In this project, experimental data of the droplets speed and angle were analysed and fitted to obtain the best empirical model of the spreading law. 
The parameters in the model were adjusted using the python function 'polyfit' from numpy until a best fit was found. Models with different order of polynomials were also compared in terms of how accurate they are to the fit.

## Second Project: Forced Oscillations

Numerical integration method is a convenient approach for physicists to predict the dynamics of a system if the underlying physics is too complicated. One example of this is a double pendulum.
In this project, the numerical integration approach was studied and applied to a simple oscillation system of a pendulum under different conditions such as damping and forced oscillation by an external force F(t). The following four integration method were used and compared in terms of their accuracy:
1. Euler
2. Improved Euler
3. Verlet
4. Euler-Cromer

Bonuses include looking into the case where the pendulum is oscillated by a sinusoidal wave function and resonance under different damping conditions.

## Third Project: Neutron Transport

In this project, Monte Carlo simulations were utilized to generate a large amount of neutron samples that penetrate a slab with fixed thickness and investigate the particle transport process.
By using a discrete Markov chain, the scattering path of a neutron was constructed, which either resulted in the particle being absorbed, transmitted or reflected out of the slab. Therefore, the transmittion and absorbtion rate of the neutron was analyzed based on our given data of their associated cross sections.
Several plots were plotted to display the random path a particle takes in its scattering process. The randomness in the path as well as the attenuation length of the slab was also explored. In addition, the notebook also features a highly efficient code that simulates the neutron transport process, which utilizes the large numpy array feature.

Yeah baby!


