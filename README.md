# Remotely-Operated-Vehicle-Dynamics-and-Control
Unfortunately Cannot Share all Files here since some of them are proprietry. Here are the ones that are completely my own

You run the equilibrium point code based on the manoeuvre being performed, then linearize the model about the equilibrium point. Then, you can run a simulink file for the linearized model.

Other matters I worked on:

1.	Extensive literature review on Vehicle dynamic models used for underwater autonomous vehicles
2.	Literature review of the control schemes used for UAVs including PID, cascaded PID control, Sliding motion control, H infinity control
3.	Determine the equilibrium point using a matlab script that allowed us to change that depending on what the rov was doing
4.	Model linearization about the selected equilibrium point
5.	Modelling the linear and nonlinear models in Simulink and comparing them in the peresence and absence of disturbances
6.	Devising a PID control scheme and tuning it
7.	Devising an H-infinity control scheme for the Autonomous Underwater vehicle as well as a Simulink model for that to test its ability to respond to disturbances and tune weights to some extent (get a ballpark idea)
