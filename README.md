# Computational-approaches-to-neuroscience

This is a jupyter book containing a series of descriptions and codes for a young student of computaitonal neuroscience to quickly gain familiarity with the field. This is based on the lectures and tutorials taken at the Computaitonal Approaches to Memory and Plasticity.

\## Implies phase 2.

## PREFACE
This book is organized by keeping two things in mind, one the pedagogical flow required to understand computational models from the point of view of a modeller, and the second 
## INDEX 
0. Remedials
    * Introduction to Jupyter notebook and Python
    * Differential equations
    * Dynamical systems - basics
    * Linear Algebra (?) 
    * Simulation basics (Euler's method, integration timesteps, stiff systems, etc.)
  
1. Neuron as a spherial elephant
    * Integrate and fire (IF neuron)
    * Leaky integrate and fire (LIF neuron)
    * Conductance model
    * Modeling ion channels
    * Abstract Neuron models
      * FHN, Izikevich, etc.

2. With 5 parameters, I can make it wiggle its trunk
    * Isopotential neurons - recap
    * Rall's law
    * D-lambda rule
    * Simulating passive neurons with beautiful morphologies
        * Downloading morphology files from various databases.
    * Ion channel distributions
      * Can be split later to its own chapter, for instance, to simulate active dendrites.
  
3. At the end of the day, it's all chemistry
    * Simulating chemical reaction networks
    * Let's fast forward to the end, shall we? (No dynamics, just the steady states)
      * Bistable systems
    * I like to move it, move it (Dynamics)
      * Bistable systems
      * Oscillators
    * I need some space (diffusion)
      * Turing model
    * How many particles, again? (Stochastic simulation)
    * All in ( Single particle tracking simulations)
    * Multi-compartment models ##
    * Hybrid models ##
    * Plasticity : BCM Curve (Calcineurin, CamKII)

4. Everything is connected (Putting together electrical and chemical dynamics)
    * Downloading morphologies, distribute ion channels, put in spines.
    * Add chemistry and use adapaters to couple the chemistry to electrical dynamics.
    * Wiggly spines (Structural plasticity)
    * Simulating a detailed model
    * Structural plasticity (More stuff to come here, perhaps from CAMP 2019?) ##

5. Networks
    * Feedforward Networks
      * SynFire Chains
      * Kremkow, Kumar
      * Tim Vogels ## 
    * Recurrent Networks
      * Brunel, 2000
      * Ostojik, 2014
    * Neural coding
    * Network correlations
    * EI Networks
    * Learning Rules
      * LTP
      * STDP
        * Song et al
      * BCM Curve
    * Short Term Plasticity
      * Tsodyks and Markram
      * Band passing network input

6. Learning in neuronal networks
    * Perceptron Learning Rule
    * XOR Problem
    * Hopfield Networks (# Could also be in Networks module)
    * Backpropagation
      * Algorithm
      * Problems with biological implementation
    * Spiking neural networks that learn
      * Echo state networks
      * Sophie Deneve's model
      * FORCE
      * FOLLOW
    * Reinforcement Learning
  
7. Systems and Behavior
    * Rate models
    * Place cell models
    * Neural Coding (Rate and Time codes) (# Currently also in networks module)
      * Golisch and Meister
      * Receptive Fields
    * Sequences and sequence learning (?) ##
