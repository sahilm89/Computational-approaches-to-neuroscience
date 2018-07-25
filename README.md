# Computational-approaches-to-neuroscience

This is a jupyter book containing a series of descriptions and codes for a young student of computaitonal neuroscience to quickly gain familiarity with the field. This is based on the lectures and tutorials taken at the Computaitonal Approaches to Memory and Plasticity.

\## Implies phase 2.

## PREFACE
This book is organized by keeping two things in mind, one the pedagogical flow required to understand computational models from the point of view of a modeller, and the second 

## INDEX 
0. Remedials
    1. Introduction to Jupyter notebook and Python
    2. Differential equations
    3. Dynamical systems - basics
    4. Linear Algebra (?) 
    5. Simulation basics (Euler's method, integration timesteps, stiff systems, etc.)
  
1. Neuron as a spherial elephant
    1. Integrate and fire (IF neuron)
    2. Leaky integrate and fire (LIF neuron)
    3. Conductance model
    4. Modeling ion channels
    5. Abstract Neuron models
        1. FHN, Izikevich, etc.

2. With 5 parameters, I can make it wiggle its trunk
    1. Isopotential neurons - recap
    2. Rall's law
    3. D-lambda rule
    4. Simulating passive neurons with beautiful morphologies
        1. Downloading morphology files from various databases.
    5. Ion channel distributions
        1. Can be split later to its own chapter, for instance, to simulate active dendrites.
  
3. At the end of the day, it's all chemistry
    1. Simulating chemical reaction networks
    2. Let's fast forward to the end, shall we? (No dynamics, just the steady states)
      * Bistable systems
    3. I like to move it, move it (Dynamics)
      * Bistable systems
      * Oscillators
    4. I need some space (diffusion)
      * Turing model
    5. How many particles, again? (Stochastic simulation)
    6. All in ( Single particle tracking simulations)
    7. Multi-compartment models ##
    8. Hybrid models ##
    9. Plasticity : BCM Curve (Calcineurin, CamKII)

4. Everything is connected (Putting together electrical and chemical dynamics)
    1. Downloading morphologies, distribute ion channels, put in spines.
    2. Add chemistry and use adapaters to couple the chemistry to electrical dynamics.
    3. Wiggly spines (Structural plasticity)
    4. Simulating a detailed model
    5. Structural plasticity (More stuff to come here, perhaps from CAMP 2019?) ##

5. Networks
    1. Feedforward Networks
        1. SynFire Chains
        2. Kremkow, Kumar
        3. Tim Vogels ## 
    2. Recurrent Networks
        1. Brunel, 2000
        2. Ostojik, 2014
    3. Neural coding
    4. Network correlations
    5. EI Networks
    6. Learning Rules
        1. LTP
        2. STDP
            - Song et al
        3. BCM Curve
    7. Short Term Plasticity
        1. Tsodyks and Markram
        2. Band passing network input

6. Learning in neuronal networks
    1. Perceptron Learning Rule
    2. XOR Problem
    3. Hopfield Networks (# Could also be in Networks module)
    4. Backpropagation
        1. Algorithm
        2. Problems with biological implementation
    5. Spiking neural networks that learn
      1. Echo state networks
      2. Sophie Deneve's model
      3. FORCE
      4. FOLLOW
    6. Reinforcement Learning
  
7. Systems and Behavior
    1. Rate models
    2. Place cell models
    3. Neural Coding (Rate and Time codes) (# Currently also in networks module)
        1. Golisch and Meister
        2. Receptive Fields
    4. Sequences and sequence learning (?) ##
