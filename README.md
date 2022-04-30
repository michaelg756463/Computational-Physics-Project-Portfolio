# Computational-Physics Project Portfolio

## Introduction
This Github Repository contains a collection of Juptyer Notebook files that pertain to different physics modeling projects. These projects are the result of combining topics from theoretical physics with computational modeling. The various physical topics explored include the modeling of electron flow in a metal, modeling a double pendulum, re-creating a paper-toss game using air resistance, modeling different boundary conditions for a chain of oscillators, and visualizing the time-evolution of a radiative electric field due to an oscillating electron. The difficulty of the theoretical physics needed to understand these projects is at an undergraduate college level. Each project is written in Python and formatted in a way in which the audience is given background information regarding the project as well as the methods and assumptions used to execute the program. 

## Projects
Below are links to each of the Juptyer Notebooks corresponding to its project. Brief descriptions of each project are given, but a more in-depth introduction is given within each Jupyter Notebook. 

* [Electron Flow in Copper Metal](https://www.google.com) - The Drude Model of electrical conduction is used to simulate electron flow in a copper wire. The "copper wire", is modeled as a lattice of spherical copper nuclei. The electrons flow through the lattice of copper nuclei under the influence of a uniform electric field. The average drift speed is then calculated within the program. The vypython package is used to animate this simulation.

* [Double Pendulum](https://www.google.com) - The Double Pendulum is a system first introduced in a Classical Mechanics course. This system is very interesting as it exhibits chaotic behavior for a given set of initial conditions. This notebook explores the double pendulum with different sets of initial conditions. To model the system, numerical integration is used to solve four different ordinary differential equations. The vpython package is used to visualize the time evolution of this system.

* [Ball Toss Simulation](https://github.com/michaelg756463/Computational-Physics-Project-Portfolio/blob/main/Ball_Toss_Project.ipynb) - "Paper Toss" was a game released on IOS in which a player can swipe to toss a paper ball into a trash can. This notebook attempts to recreate this game with the parameters of a baseball while accounting for air resistance. Numerical integration is once again used to model the trajectory of the ball while including variable air resistance and a backwind. Players must choose an angle in order to aim the ball towards the target. The user interface is run using vpython. 

* [Chain of Oscillators](https://www.google.com) - Numerical integration is a useful tool for solving sets of differential equations for a given system. The issue arises when you have multiple systems that are coupled to each other. A chain of N - coupled oscillators is a perfect example in which it would be computationally taxing to numerically integrate. Linear algebra is a very useful tool to handle this type of system in order to find solutions to these complex systems. The SciPy Linear Algebra package is a powerful tool and is used in order to investigate a chain of N - coupled oscillators with different boundary conditions.

* [Radiative Electric Field](https://www.google.com) - Electrodynamics is a field that describes electric and magnetic fields as they interact with matter and evolve over time. Visualizing these dynamical fields is no trivial task and requires a great understanding of electrodynamical theory as well as handling mass calculations and visualizations efficiently. This notebook explores a radiative electric field due to an accelerating electron. This electron oscillates within a hydrogen nucleus and the evolution of this field is visualized with vpython once again. eeee

## Citations and Acknowledgements

* Dr. Aaron Titus, Professor of Physics and Astronomy, High Point University.
* Griffiths, David J. Introduction to Electrodynamics. Cambridge University Press, 2018. 
* Wang, Jianyi Jay. Computational Modeling and Visualization of Physical Systems with Python. Wiley, 2016. 





