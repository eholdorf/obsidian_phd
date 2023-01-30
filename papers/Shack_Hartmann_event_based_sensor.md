#papers 
#eventbasedsensor

[pdf](file:///Users/u6955379/Documents/PhD/papers/Shack_Hartmann_event_based_sensor.pdf)

# Notes:
- notes local brightness changes, c.f. brightness over time (i.e. frame based sensor)
- found that event based sensor worked just as well as frame based sensor, but faster and good with low light
- thus preferrable for AO
- only detect something when there is a change in brightness over some threshold
- tracks changes in intensity in x, y and time, also tracks the polarity (i.e. positive or negative change)
- often have lots of noise - could you average over all time??, also look at machine learning to remove the noise
- can remove noise by looking at whether events are correlated or not - can look at path that you expect your target to take, i.e. can look at how far away the different events are
- the change in the intensity to trigger an event is user set
- work well under low light - thus don't need to just increase the exposure time
- 