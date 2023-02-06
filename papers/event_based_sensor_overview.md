#papers 
#eventbasedsensor 

[pdf](file:///Users/u6955379/Documents/PhD/papers/event_based_sensor_overview.pdf)

# Notes:
- respond to local brightness changes independently for each pixel
- then get a series of 'events' over the exposure time compared to a linear representation of increasing flux as with traditional frame based detector
- each event tagged with pixel position (x,y), a time t, and the polarity of the event (i.e. if the event was an increase/ decrease)
- many methods to try and decrease the noise, one such is to not include an event if it isn't associated with any other events (i.e. just a one off event in that pixel, as the noise should be fairly random)
- another interesting method is to only look at events in a particular region of interest, could be around each event if there is another event within some region of interest then keep and determine that they are correlated, otherwise ignore
- can use spot tracking algorithms to track a particular feature to see how it is moving with time, and thus how the wavefront is changing
- then has heaps of examples of testing of these sensors showing what they were used for, integration time and illumination level