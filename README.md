# Artificial Intelligence for Robots (AI4R)

Jupyter Notebooks for robotic car kits that explore the algorithms used in self-driving vehicles.

These notebooks are generally self-contained and can run without custom robotic car kit hardware. But they have been designed for porting over to robotic car kits and run real-world experiments.

Several Jupyter Notebooks have been provided:

1. **angle_extended_kalman_filter**: Sets up a 2-dimensional experiment for a robotic car to determine its x-position based upon the angle it measures to a landmark using an Extended Kalman Filter.

2. **missing_data_particle_filter**: Simulates the loss of road sensor data for a robotic car due to snow. Extends a regular Particle Filter with data augmentation to determine the car's location.

3. **dynamic_value_iteration**: Updates the optimized policy to reach a goal when the robotic car discovers addition information such as a hole in the road. Uses Markov Decision Process (MDP) Value Iteration Planning.

4. **pid_racer**: Provides an experimental template which eliminates the need for the robotic car to perform localization while allowing it to race around a circular track under a PID controller.

5. **slam_map**: Offers a very simple experimental template for regular robotic car kits that allows a robot to simultaneously localize its position while it maps a 1-dimensional environment.
