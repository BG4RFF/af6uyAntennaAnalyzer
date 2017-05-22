# AF6UY Antenna Analyzer

This is my take on Beric Dunn's (K6BEZ) Antenna Analyzer using the AD9850.  
I was first introduced to his design at least two years ago, I think at
[BayCon](http://baycon.us/).  Now that I'm installing antennas it would be
good to have a simple antenna analyzer, so of course in true ham fashion,
why not build one?

To kick things off I though simulating Beric's circuit would be a good way
to understand how it worked.  In the sim directory, you will find an LTSpice
simulation file.  Watch as the simulation runs (as the plotting should
automagically happen) you will see the DDS frequency sweep by 1MHz per step.
The plot is of [V(out2) - V(out1)].
