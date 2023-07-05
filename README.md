# Optimal-design-of-Synchronous-Reluctance-Motor
Optimal Design of a Synchronous Reluctance Motor Using BioGeography-Based Optimization
High torque density is a demanding criterion in electrical machines. Machines with permanent magnets (PM) in their structure possess this feature inherently. On the other hand, in motors with no PM material, torque density is a source of concern for machine designers. So, the optimization methods should be used in the design process to achieve the best performance in terms of torque density. Biogeography-based optimization (BBO) is a relatively new algorithm with good convergence in the least time. In this project, the structure of a synchronous reluctance (SyncRel) motor with no PM material is optimized using the BBO method.

In this study, we want to optimize the structural parameters of the SyncRel to have the best torque performance. The machine’s outer diameter and axial length are constant. So, the torque is the same as the torque density. In mathematical form, the decision variables vector can be expressed as

x = (x_1,x_2,x_3,x_4)	                                                 
Where,

x_1 = Inner radius of the stator yoke;
x_2 = Turns per coil;
x_3 = Inner radius of the rotor yoke;
x_4 = Radius of the segmented parts of the rotor;

We have the following constraints for the decision variables:

55 ≤ x_1 ≤ 58				
40 ≤ x_2 ≤ 60 (an integer in the interval)		
10 ≤ x_3 ≤ 14			
34 ≤ x_4 ≤ 37           				 

For objective function, we use the minimization form,

Cost function = 1/(Average Torque)                            

Optimization problem: min⁡{Cost function}    @ s.t.Torque ripple<30%


1. If you want to connect MATLAB and ANSYS Maxwell (ANSYS Electronics Desktop), This file will help you.
2. If you want to optimize the design of a synchronous reluctance motor with a direct interface between MATLAB and ANSYS, this file will help you.
3. If you want a paper with complete simulation files, this file will help you.
4. If you want to have the simulation of a synchronous reluctance motor, this file will help you. In the simulation, the boundary
    conditions, excitation currents, meshing, and design steps are explained in complete detail.
5. If you want to know the difference between the initial and optimal designs of electric motors, this fill will help you.
6. If you want to know the nuances of selecting decision variables and objective functions for a design optimization problem,
    this file will help you.
   
![Torque performance](https://github.com/toohidsharifi/Optimal-design-of-Synchronous-Reluctance-Motor/assets/126771405/777204ab-ae6a-4753-bad9-9a8661b6aaaa)

![Matlab](https://github.com/toohidsharifi/Optimal-design-of-Synchronous-Reluctance-Motor/assets/126771405/b5d1d4ed-d65b-46c4-98f8-81aa13b0ad5d)

![Matlab-ANSYS](https://github.com/toohidsharifi/Optimal-design-of-Synchronous-Reluctance-Motor/assets/126771405/1c9e0098-444d-49bd-8635-2cbdfc7cd130)

![Motor](https://github.com/toohidsharifi/Optimal-design-of-Synchronous-Reluctance-Motor/assets/126771405/cadd95f9-da3a-4c90-b735-1f372bece131)

![BBO](https://github.com/toohidsharifi/Optimal-design-of-Synchronous-Reluctance-Motor/assets/126771405/77e019d2-abb8-47ec-bcdd-16dfb2ec728e)


In this project, the design and optimization of a SyncRel machine were conducted using the BBO algorithm. From various comparisons between the initial and the optimal motors, we concluded that the BBO algorithm shows effectiveness in optimizing the electrical machines. The necessity for less number of iterations and high convergence speed were the most valuable features of the BBO. As an important parameter, the number of function evaluations in the BBO is calculated.
