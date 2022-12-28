# Deep-Q-Learning-with-Tensorflow
Several Deep Q-learning problems with Tensorflow and Gym library.

## LunarLander-v2

The task for a neural network is to land in the space between two flags and there are for actions allowed: do nothing or fire left, right or bottom engine. 

The first episode ended with a crash:

![Alt Text](https://github.com/KornelWitkowski/Deep-Q-Learning-with-Tensorflow/blob/main/gifs/LunarLander-v2/video-start.gif)

After a few hundreds epochs the neural network is able to keep the lander safe. However, it is not able to land in the episode time.

![Alt Text](https://github.com/KornelWitkowski/Deep-Q-Learning-with-Tensorflow/blob/main/gifs/LunarLander-v2/video-middle.gif)

In the end of the traning process the landing is done without any troubles.

![Alt Text](https://github.com/KornelWitkowski/Deep-Q-Learning-with-Tensorflow/blob/main/gifs/LunarLander-v2/video-end.gif)


## LunarLander-v2 - Continuous 

The goal is the same as in the previous problem, but this time a neural network has to choose values from a continous domain. It is solved with the Normalized Advantange Function and by discretization of the domain. 

## Cart Pole 

A neural network has to keep the pendulum in the vertical position for as long as possible. The action space is discrete.

![Alt Text](https://github.com/KornelWitkowski/Deep-Q-Learning-with-Tensorflow/blob/main/gifs/Cart_Pole/video-end.gif)

## Mountatin Car

In this task, the car should reach a flag in the right hill. Very beginnings of the learning process:

![Alt Text](https://github.com/KornelWitkowski/Deep-Q-Learning-with-Tensorflow/blob/main/gifs/MountainCar/MC-start.gif)

End of the training:

![Alt Text](https://github.com/KornelWitkowski/Deep-Q-Learning-with-Tensorflow/blob/main/gifs/MountainCar/MC-end.gif)
