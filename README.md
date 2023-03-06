# Markov-Chain-based-Simulator

Program that simulates customer behaviour in a supermarket based on Monte Carlo Markov Chain simulation analysis. The project involed 4 main stages: exploring the data (pandas wrangling), calculating transition probabilities, implementing a Markov Chain-based simulator adding Customers to the simulation based on a Poissonian randomness, and creating a program to visualize how customers move through the supermarket through animation. The program uses classes in a python program, Markov Chain modeling, and a Monte-Carlo simulation.

![output_final](https://user-images.githubusercontent.com/121929719/222722433-5e0df4dd-b142-4419-b8be-75a3ccdcd451.gif)

The Customers start at entrance and then are moved along the supermarket and through different locations named: 'fruit', 'drinks', 'dairy', 'spices', 'checkout'. The probabilites of the movement between these sections are calculated based on real data. As the Customer approaches 'checkout' the code removes this Customer.

