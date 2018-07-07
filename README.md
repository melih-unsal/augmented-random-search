# Augmented Random Search (ARS)

Ars is a latest A.I algorithm proposed on march 2018.
It is based on shallow learning method. It has a input layer which accepts a vector
of the environment state and then after multiplying them with the weights it gives an output
to the environment.
It's different from other reinforcement learning models because it doesn't have any deep neural net
between its input and output layer.It also doesn't work on action space instead, it works on policy space.

## Weights optimisation
ARS uses a different approach to optimise its weight. Unlike other algorithms, it uses finite difference approach
to optimise the weights.
f'(x) = summation(f(a+h)-f(a)) where is a very small pertubation.

## Performance
It almost 15 times faster than other reinforcement algorithms of 2017. 

## Shallow Learning
![slide4](https://user-images.githubusercontent.com/35776307/42407405-9cfdf854-81d9-11e8-9d00-1c6a99080411.png)

## Reinforcement Learning
![deep-reinforcement-learning-with-a-serious-game-as-environment-and-an-artificial-neural](https://user-images.githubusercontent.com/35776307/42407420-e8820446-81d9-11e8-83c8-f1c5226bb12a.jpg)
source -- https://www.researchgate.net/profile/Uwe_Borghoff/publication/316890217/figure/fig4/AS:493516439724035@1494674896356/Deep-Reinforcement-learning-with-a-serious-game-as-environment-and-an-artificial-neural.jpg

## Testing ARS on pybullet's Half-Cheetah environment
End Result:- Half-cheetah will run on environment.
Agent is referred to as Half-cheetah
#### Training the agent performance on environment for 1000 steps of training
In the beginning of train the agent will barely stand on the environment. And after steps of training it will learn how to stand
and run.

##### At the start of training
![ezgif com-optimize](https://user-images.githubusercontent.com/35776307/42407542-5a4d2400-81dc-11e8-9c61-c646616bf77e.gif)

##### After training on steps=20
![ezgif com-gif-maker1](https://user-images.githubusercontent.com/35776307/42407630-9c330b0e-81dd-11e8-9537-dfe42ba8b5d8.gif)

##### After training on steps=50
![ezgif com-gif-maker2](https://user-images.githubusercontent.com/35776307/42407631-9c72b998-81dd-11e8-8bb5-05717dc0adb9.gif)

##### After training on steps=80
![ezgif com-gif-maker2](https://user-images.githubusercontent.com/35776307/42407631-9c72b998-81dd-11e8-8bb5-05717dc0adb9.gif)


It can be seen the improvement of agent on environment from above gif's.
