#papers 
#wavefrontsensor
#toread 

[pdf online](https://ir.canterbury.ac.nz/bitstream/handle/10092/1645/thesis_fulltext.pdf?sequence=1&isAllowed=y)

# Notes:
- a PhD thesis, so hopefully a good in depth overview, from 2008 so worth noting that 15 years has passed and the technology is likely more advanced
- need AO as space telescopes cost ==dramatically== more c.f. to ground based telescopes for a given mirror size
- so AO measures the distortion to the light wavefront, namely using a wavefront sensor
- this is then used to move a deformable mirror which corrects the wavefront to remove the effects of turbulence
- the main WFS used are Shack-Hartmann, pyramid, geometric and curvature (in CaNaPy using pyramid and Shack-Hartmann)
- turbulence typically degrades quality to be ~ 1'' irregardless of the telescope size 
	- diffraction limit is $1.22 \dfrac{w}{d}$
	- thus for anything over 0.12m diameter, need AO to make the most of the mirror (i.e. there will be distortions)
- AO can be used in:
	- spectroscopy - the smaller the slit the higher the resolution, so make image smaller so make the slit smaller
	- direct imaging - make the image clearer
	- interferometry - need path length to be very accurate as use several telescopes, thus need turbulence to be corrected very well
- turbulence occurs from the mixing of air of different temperatures and pressures
- turbulence starts off on large scales, but through friction and viscosity, makes its way to smaller scales, then to heat
- Sir Isaac Newton - =="Tremors of the atmosphere"== , described by the =="twinkling of fixed stars"
- turbulence occurs through entire atmosphere, but believed that it is the strongest in the first 10km up from the Earth's surface (ground layers)
- ## Wavefront Sensors:
	- used to estimate aberrations caused by the atmosphere
	- do this by measuring the effects on light
	- typically divide the aperture up, and measure the slope of the wavefront between these smaller regions
	- look at how the image is displaced over time, and this is a measure of the slope
	- one limitation of this, is require typically ~ 20 photons in each subaperture, so doesn't work well for dim objects
	- thus, use different object to the target which is brighter (NGS, or LGS to get more sky coverage)
	- 