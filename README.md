# cartpole-v1-policyGradient
## Description

The CartPole environment consists of a pole that is attached by an un-actuated joint to a cart that moves along a frictionless track. The pendulum starts upright. The goal is to keep the pole upright and prevent it from falling over by increasing or reducing the cart’s velocity. The system is controlled by applying a force of +1 or −1 to the cart. A reward of +1 is provided for every timestep that the poleremains upright, including the termination step. The observations in the CartPole-v1 environment we are using in this assignment are four dimensional and continuous:

![image](https://user-images.githubusercontent.com/62834697/178379496-e312b684-a4a7-4646-b3ed-4fa48832b544.png)

At each timestep, one of two discrete actions can be taken:

![image](https://user-images.githubusercontent.com/62834697/178379615-c4bf59a5-24a5-4a51-b306-4f96b098ae11.png)

For each timestep in an ongoing episode a reward of +1 is given. The episode ends when
* the pole is more than 12 degrees from vertical, or
* the cart position is more than 2.4 (center of the cart reaches the edge of or the display), or
* episode length is greater than 500.

#### Getting Started:
1. Clone the repo :
```shell
$ git clone https://github.com/kumar-sanjeeev/cartpole-v1-policyGradient.git
```
2. Install the dependencies by running `requirements.txt` file
```shell
$ pip install -r requirements.txt
```
