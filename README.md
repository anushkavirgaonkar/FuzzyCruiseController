# FuzzyCruiseController
Implementation of Greg Viot’s Fuzzy Cruise Controller using Fuzzy Logic.

## Introduction
Many fuzzy control systems are tasked to keep a certain variable close to a specific value. For instance, the speed of the cruise needs to be kept relatively constant. A fuzzy control system links fuzzy variables using a set of rules. These rules are simply mappings that describe how one or more fuzzy variables relates to another. Using these rules, a system is developed which gives the output corresponding to the set of input values. 

## Implementation
The system is implemented in the Python programming language using scikit-fuzzy, which is a fuzzy logic Python package that works with numpy arrays. We create the three fuzzy variables - two inputs, one output (error, delta, output).
<p align="center">
  <img src="https://github.com/anushkavirgaonkar/FuzzyCruiseController/blob/master/assets/fig1.png" height="400" width="500">
</p>

We then define the complex set of rules in the fuzzy system.
<p align="center">
  <img src="https://github.com/anushkavirgaonkar/FuzzyCruiseController/blob/master/assets/fig2.png" height="600" width="500">
</p>
Based on these rules, the fuzzy controller system predicts the output values.
<p align="center">
  <img src="https://github.com/anushkavirgaonkar/FuzzyCruiseController/blob/master/assets/fig3.png" height="600" width="500">
</p>
With helpful use of Matplotlib and repeated simulations, we can observe what the entire control system surface looks like in three dimensions.
<p align="center">
  <img src="https://github.com/anushkavirgaonkar/FuzzyCruiseController/blob/master/assets/fig4.png" height="600" width="500">
</p>



