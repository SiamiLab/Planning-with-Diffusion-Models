# Planning-with-Diffusion-Models

A motion planning framework that combines energy- based diffusion models with artificial potential fields for robust real time trajectory generation in complex environments.


The following experiments demonstrates the validity of the planned trajectories in a physical setup, we conducted experiments using sensor-rich, 1/10-scale RC QCars.



## Experiment 1
In this experiment, the robots operate within a $2 \times 2 \, m^2$ environment, starting from the top of the field. The evader's objective is to reach its designated goal on the left-hand side while being pursued by the pursuer. 

The video provides a representation of the experiment. On the right, the real lab setup is shown, where the robot highlighted in green serves as the evader, while the one highlighted in red acts as the pursuer. A purple dashed line indicates the initial high-level trajectory. The environment is free of static obstacles, allowing the robots ample space for movement, given the constraints of our lab setup and the non-holonomic nature of the robots. On the left, the trajectories of both the evader and pursuer are visualized over time, along with their initial and final positions.


https://github.com/user-attachments/assets/c88f1a20-48ed-4298-bc87-19caf8bfc9d0




## Experiment 2
Here, we illustrate the second experiment conducted in the physical world. In this experiment, we introduce a new unseen static obstacle at the center of the lab, along with a new set of initial positions and a final goal for the evader.

In the video, the right side shows the real lab setup, where the robot highlighted in green represents the evader, the robot highlighted in red represents the pursuer, and the purple area indicates a static obstacle placed at the center of the lab. The purple dashed line shows the initial high-level trajectory. On the left, the final trajectories of the evader and pursuer over time are depicted, along with their initial and final positions.


https://github.com/user-attachments/assets/880a61e9-ceb9-4302-bfcd-b6d39c5ce386




## Experiment 3
The third experiment replicates the second experiment; however, the static obstacle at the center has been removed to highlight its effect on the final trajectories of the robots.

In the video, the right side shows the real lab setup, where the robot shown in green represents the evader and the robot shown in red represents the pursuer. The purple dashed line shows the initial high-level trajectory. On the left, the final trajectories of the evader and pursuer over time are depicted, along with their initial and final positions.


https://github.com/user-attachments/assets/690ec261-bb33-4c3f-a45d-996b216e849c



