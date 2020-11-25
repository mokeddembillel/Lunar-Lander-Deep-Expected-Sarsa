# Lunar-Lander-Deep-Expected-Sarsa
This project is about using deep expected sarsa with tensorflow to solve the lunar lander problem with hyperparameter tuning and result's analysis

#These points are important read them please:

-all data and models are in results folder 

-folder tests is just for you if you want to test something

-if you want to plot the data, you don't need tensorflow just python and matplotlib

-you need TensorFlow 2.3 for it to work

#the code is structured this way: 

-imports

-replay buffer class

-expected sarsa  network

-softmax and argmax helper functions

-agent class 

-lunarlander class

-loading, parsing plotting helper functions

-run experiment function for testing egreedy and softmax

-run experiment function for testing batch size and replay steps

-run experiment normal run 

-setting all learning parameters, data and the call for the run experiment function

-cell for loading data and defining the loaded variable (run it before trying to plot or test the agent)

-cell to compute averages

-cell to plot same : plot all data (rewards, loss, episode steps) for each type of tests

-cell for choosing best batch size and number of replay steps

-cell for choosing best softmax tau and step-size 

-cell for choosing best e-greedy epsilon and step-size

-INFO CELL (IMPORTANT READ IT PLEASE)

-cell to load and reconstruct model

-cell to plot data of best model

-cell to test the agent

-thank you :)

