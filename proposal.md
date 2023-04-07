# Proposal

## What will (likely) be the title of your project?

Replicator Dynamics in Python

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

Code that takes in a two or three player game with a payoff matrix and gives a graph that shows if a given game has an equilibrium or not. 

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

This project will examplify replicator dynamics, a key topic in evolutionary game theory. A replicator dynamic of model of a population allows for selection to happen in a population. This is based on a payoff matrix for all the types in a population. The replicator equation that this type of modeling comes from doesn't include mutations (or the ablility to change into a different type), but with some modifications mutations can be accounted for. 

This project will create code that takes in a payoff matrix for three types in a population, initial population frequencies of different types, and probability of mutation for each of those types and produces a graphical representation of a population over a long time period. Ideally the graphs should show if a given population has an equilibrium or if it osilates between different population frequencies. For this project two types of graphs will be made. The first will be a x-y plot with the y axis being population frequencies and x axis being time. The other graph will show similar information as a 3 dimensional simplex that shows the trends of the frequencies in a population over time and will also be color coded to show how fast those changes occur. 

The first graph will be made using the Numpy package and Nashpy package along with it's replicator function. The second graph will be made using the egtplot package. 

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

I am not doing this for another course's final, but I am doing this for an honor's credit in my Game Theory course. The concepts and understanding of the graphs is what's related to my Game Theory course, but the actual coding and implementation of the packages to create graphs will be related to this course. 

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

NA

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

I will be able to graph a replicator dynamic system for two types in a population and make a 3 dimensional simplex graph using the egtplot package. 

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

To be able to graph a replicator dynamic system for three types in a population and make a 3 dimensional simplex graph. 

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

Do the above, but with the possibility of mutation of one or more type in a population. 

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I will have to carefully review the packages mentioned and how to create nice looking graphs in python. 
