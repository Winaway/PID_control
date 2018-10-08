# PID Implement Discussion
### The effect of the P, I, D component of the PID algorithm

The PID controller can be divided  into three parts.

P - Proportion Control,  aims to reach the reference  trajectory as close as possible. It is the fundamental control of PID, but it has a problem of overshooting.

D-Differential Control. In order to handle the problem of overshooting in Proportion Control, Differential Control was introduced . As the vehicle getting closer to the reference  trajectory, it tries to slow down the Proportion Control to get a flat fluctuation of  driving.

I - Integral Control. In the case of existing a systematic bias, Integral Control plays a role to eliminate the systematic bias.

###  Hyperparameters (P, I, D coefficients) Tuning

I chose the final hyperparameters through manual tuning. I tried a lot group of parameters. According to the performance in the simulator ,I finally chose the last hyperparameters group.