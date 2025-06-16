# waveBoundaryConditions
continuation of olaFlow implementaion of the boundary conditions for surface waves. The boundary conditions for generation and absorption of waves are rewritten in order to account for arbirtrary wind speed.
This enables for more diverse CFD multiphase simulations. Boundary conditions for inlet and outlet velocity field are adjusted to read additional wind speed, written in a vector form. Initated velocity field with same distributions in both phases is seen in Fig. below:

![velocity_1](https://github.com/user-attachments/assets/c43e75b3-c914-4436-81a2-6b3538c75367)


 The attached files can simply be copied to the original olaFlow source code and compiled.

 olaFlow implementaion can be found here: https://github.com/phicau/olaFlow

If you are using this libraries, please cite the following paper:https://doi.org/10.1016/j.oceaneng.2025.121519
