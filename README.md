# Genetic-Algorithm-CartPole-v0

Here, I have used Open AI Gym environment to simulate a simple game known as CartPole-v0 and then we will use Genetic Algorithm to automate the playing of the game. 
This project is a code implementation to run basic Genetic Algorithm in OpenAI Gym Environment.


### Problem Statement
A pole is standing upright on the cart. The goal is to balance the pole in an upright position by moving the cart left or right. 
You lose the game if the angle of the pole with the cart is more than 15 degrees.
You win the game if you manage to keep the pole balanced for given number of frames. 
For every frame you mange to keep the pole in upright position you get a ‘+1’ score.

![Cartpole](https://github.com/chiragsamal/Genetic-Algorithm-CartPole-v0/blob/master/cartpole.jpg)

### Solution
To solve this problem we will first create some random game data and then we will feed it to our GA model
which in turn will predict the movement of cart(left or right) for every frame.
