# Year 2 Computing Project B Thermodynamics Snookered

# Ball.py 
It includes two classes 'Ball' and 'Container'. Each class has methods as follows: __init__(), pos(), vel(), time_to_collision(), move(), collide() and get_patch(). You may refer to the doc string the file for the eaxct use of codes but in general, it enables calculation of times to ball-container and ball-ball collisions, the moving of the balls and the update of velocities of the balls after collision. This is for tasks 1 and 2 and further use in Simulation.py

# Simulation.py 
It includes one class 'Simulation' which can be initialised with parameters for a ball and a container object to create many balls within a container. It has methods as follows: __init__(), next_collision(), run(), kinetic_energy(), temperature() and pressure(). The run() method would produce an animation of the collisions, two histograms showing the distance between the balls and the central positions and that between every two balls for debugging and a probability vs speed plot fitted with a Maxwell-Boltzmann distribution. The details of the use of the codes may also be found in the doc string of the file. This is for tasks 3-9.

# Task_10-13.py 
It includes my codes for tasks 10, 11, 12 and 13. Here, a plot of P against T would be produced for tasks 10, 11 and 12. For task 13, the code directly accessed run() in Simulation.py to produce a plot of probabilities of speeds against the speeds with a best-fit Maxwell-Boltzmann distribution curve. 

# Task_14.py 
It includes my codes for the verification of van der Waals' law. This would produce a plot of P against T with a best-fit line of van der Waals' law to determine the value of b. 

# Error Analysis.py 
It was primarily a rough test of some of the figures used to initiate the classes. It was also used to test the animations and graphs for debugging. 
