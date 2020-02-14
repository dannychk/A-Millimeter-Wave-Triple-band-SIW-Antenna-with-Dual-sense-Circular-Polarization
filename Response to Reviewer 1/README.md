## Response to comment 6:
We added the simulated E-field distributions at 38 GHz at the phase of 0 degrees and 90 degrees in the latest manuscript in Fig. 3(c) and Fig. 3(d). In order to verify the LHCP at 38 GHz, we also provide the E-field distributions at the phase of 0°, 45°,90°and 135° as shown the followingfigure . It shows the polarization at 38 GHz is LHCP.<div align=center><img src="https://github.com/dannychk/A-Millimeter-Wave-Triple-band-SIW-Antenna-with-Dual-sense-Circular-Polarization/blob/master/Response to Reviewer 1/Upper_band_LHCP.png" width="850" height="220" /></div>

## Response to comment 7:
 The situation that the measured AR bandwidths look better than the simulated ones may be caused by the following factors:
1．	Frequency resolution in simulation. In the measurement, the frequency resolution is 0.01 GHz. However, considering simulation efficiency, the frequency resolution for AR was set to be 0.5 GHz in our previous CST simulation which will introduce a little bit error in simulation. The simulated AR with different frequency resolution are shown in the following figure from which it can be observed a high frequency resolution gives a little wider AR bandwidth. We have updated the simulation results with a frequency resolution of 0.01 GHz in Fig. 14 of the modified manuscript. 

<div align=center><img src="https://github.com/dannychk/A-Millimeter-Wave-Triple-band-SIW-Antenna-with-Dual-sense-Circular-Polarization/blob/master/different scale AR comparison.png" width="500" height="300" /></div>

2. The inaccuracy of the parameters of dielectric substrate, not only the dielectric constant but also the loss tangent. 

3. The inaccuracy of the connector. In our design, Southwest Microwave 2.92 mm end launch connector is used for measurement. However, we can’t model this connector perfectly in simulation because of its complicated structure.


## Response to comment 10:
We have read Chapter 5 “Circular Disk and Ring Antennas” in [F], and we also carefully checked the operational mode in the circular SIW cavity before etching the circular slot at 38 GHz. The current distribution, E-field distribution and H-field distribution are shown in the following figure, as well as Figure 5.2 in Chapter 5 of [F]. Comparing these figures, we find the SIW cavity do operates in TM210 mode at 38 GHz and the radius of this SIW cavity satisfies the formula (Equation (1) in the latest manuscript) of TM210 mode. 

<div align=center><img src="https://github.com/dannychk/A-Millimeter-Wave-Triple-band-SIW-Antenna-with-Dual-sense-Circular-Polarization/blob/master/Response to Reviewer 1/TM210.png" width="850" height="292" /></div>

<div align=center><img src="https://github.com/dannychk/A-Millimeter-Wave-Triple-band-SIW-Antenna-with-Dual-sense-Circular-Polarization/blob/master/Response to Reviewer 1/TM210_Modle.png" width="850" height="292" /></div>

In order to make this cavity radiate, we etch a circular slot in the cavity. After etching the slot, TM210 mode is disturbed and the E-field distribution in the circular slot is shown in Fig. 3(b) of the latest manuscript which is similar with the fundamental mode of a conventional ring slot. So we conclude that the upper band evolves from TM210 mode of SIW cavity to the fundamental mode of ring slot. Then a circular patch is placed into the slot for lower and middle band radiation which doesn’t affect the operating mode of upper band.