# thermopile curvefit
Sensors can provide data which can have missing data points and random noise. In such a case, it is typical to identify a mathematical model that can better represent the data with a minimal influence from noise and missing data points. Finding parameters of this model is called curve fitting.

The code below was used to fit data to identify a model for data that came from a thermopile. The thermopile was fed with infrared rays from a black body radiator.
The black body radiator was brough up to peak temperature and an inbuilt shutter was opened and closed @ 1Hz frequency to identify the time constant of the thermopile. 

It creates multiple graphs that visualizes fitting, from the rising and falling edeges of the signal seperately and parameters a, b and c are calculated to model the first order step response. 
