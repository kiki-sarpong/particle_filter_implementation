# particle_filter_implementation

### This is a project demonstration of a particle filter implementation in python. <br/>
In this project, a simple autonomous "roomba-like" robot is visualized with openCV. The robot moves <br/>
around the cyclic environment and avoids any landmarks in its path. This is just a simple routine for the robot to <br/>
turn a random direction away from the obstacle anytime it detects an obstacle too close to it.
As the robot randomly moves through the environment, a particle filter state estimation algorithm is run to predict the current state of the robot.<br/>
![image](https://user-images.githubusercontent.com/17696533/121077438-a1062d80-c7a5-11eb-8b5c-b41ac3750849.png)

## Project description:
- A robot class is created with basic robot functions for movement, sensing, etc
- A main robot object serves as the main robot and multiple other robot objects serve as the particles
- The robot movements are applied to the particles and weights are calculated based of the distances to landmarks,movement noise and measurement uncertainty
- Resampling is done to get rid of particles that are unlikely and keep particles with higher state estimation probability

![image](https://user-images.githubusercontent.com/17696533/121079316-f9d6c580-c7a7-11eb-9539-fa6ef4404289.png)
![image](https://user-images.githubusercontent.com/17696533/121079331-fe02e300-c7a7-11eb-8d11-795de60f523b.png)
![image](https://user-images.githubusercontent.com/17696533/121079350-03602d80-c7a8-11eb-8c86-e4ac92f05cb9.png)
![image](https://user-images.githubusercontent.com/17696533/121079367-08bd7800-c7a8-11eb-96ae-a65f54c97c43.png)
![image](https://user-images.githubusercontent.com/17696533/121079389-0ce99580-c7a8-11eb-8c91-ab5f2081a62f.png)
