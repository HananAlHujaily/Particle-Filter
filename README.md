# Particle-Filter

The implementation involves several steps to estimate the trajectories of Balls No. 2 and No. 3: Particle Initialization, Particle Propagation, Measurement Update, Resampling, and Estimation of Trajectory. In the Particle Initialization step, a set of particles is initialized to represent the possible states of the system. Each particle contains information about the position and velocity of a ball, and they are randomly generated based on initial understanding or assumptions about the state distribution. Next, in the Particle Propagation step, the particles are moved forward in time in each iteration using a motion model that considers the laws of motion and the effects of gravity.
