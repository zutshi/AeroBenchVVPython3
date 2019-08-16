﻿<p align="center"> <img src="gcas_py.gif"/> </p>

# AeroBenchVVPython Overview
This project contains a python version of models and controllers that test automated aircraft maneuvers by performing simulations. The hope is to provide a benchmark to motivate better verification and analysis methods, working beyond models based on Dubins car dynamics, towards the sorts of models used in aerospace engineering. Roughly speaking, the dynamics are nonlinear, have about 10-20 dimensions (continuous state variables), and hybrid in the sense of discontinuous ODEs, but not with jumps in the state. 

This is a python port of the original matlab version, which can can see for
more information: https://github.com/pheidlauf/AeroBenchVV

# Required Libraries 

The following Python libraries are required (can be installed using `sudo pip install <library>`):

`numpy` - for matrix operations

`scipy` - for simulation / numerical integration (RK45) and trim condition optimization 

`matplotlib` - for animation / plotting (requires `ffmpeg` for .mp4 output or `imagemagick` for .gif)

`slycot` - for control design (not needed for simulation)

`control` - for control design (not needed for simulation)



### Release Documentation
Distribution A: Approved for Public Release (88ABW-2017-6379)
