#Physical Audio Signal Processing
Notes on my readings
Table of Contents

[TOC]
##Physical Signal Models
A successful **model** will accurately predict the outcome of any experiment given the same input conditions and initial state.
####Physical Models
**Physical models** are the rescalled physical version of actual objects. 
####Computational models
These are mathematical models, which can be studied by computer simulations. These contains phenomenons that dont have a readily avaliable analytical solutions, such as 

 - Flight simulation
 - Protein folding models
 - Weather Forcasting models
 - Earth simulation and etc.,

####Physical Signal Models
Modelling of hysical signals, such as signal of an instrument like guitar
####The science loop
This loop playing the role of designing a **successful model**
The loop is 

1. Observations
2. Model construction
3. Comparison of simulated observations to real-world observations
4. Model refinement
5. Go to step 3

###Model Types
Many type of models, such as

 1. Recordings
 2. Structured Recordings
 3. Spectral Models
 4. Virtual Analog models
 5. Physical Models
 
 Here, 1 through 4 are called _non physical models_

And the _subject_ of this note is **Physical Models**
And is about physical modelling of _**Musical Instruments & Audio Effects**_
 
 
## Some Backgrounds
### Newtons Laws of motion
It states that Force is Mass times Acceleration. i.e,
$$f = m.a$$
####ODE
Ordinary Differential Equations derives from **Newton's law of motion** with _time_ being applied, such as
$$f(t) = m.a(t) = m.\ddot x(t)$$

where $a(t)$ is the second derivative of _position_ w.r.t. time, given by
$$\ddot x(t) = \frac {d^2x(t)}{dt^2},\text {the } \text{acceleration w.r.t. time}$$ 

> Written with [StackEdit](https://stackedit.io/).
