## 2.87 GHz Microwave Signal Generator

This project contains a 2.87 GHz fractional-N frequency synthesizer based microwave generator in skywater 130nm technology. This frequency synthersizer makes use of a phase locked loop to produce the output frequency. The PLL consists of a phase detector, charge pump, loop filter, varactor based 3 stage voltage controlled oscillator and multi-modulus divider.

## Project implementation
The figure below shows the block diagram for the 2.87 GHz fractional-N sythesizer implemented in skywater 130nm tecnology.  
![PLL loop](Images/PLL.png "Fractional -N synthesiszer PLL")


### Simulation results
To validate our circuit, we have tested it in 180 nm technology and the results for the same are shown in the figure below.
#### Phase Frequency Detector
![](Images/pfd.png)
#### Voltage controlled Oscillator
![](Images/ro_cbank_var_post.png)
#### Fractional-N divider
![](Images/div.png)
### Sources
This repository mainly contains all the required building blocks for the implementation of the PLL(gds/mag/netlists). We have the complete fractional-N PLL loop, individual blocks - PFD, fresctional-N divider, VCO, charge pump and loop filter. In addition to these we have combinations of phase dectector - divider and VCO - divider.  

### DOCUMENTATION UNDER DEVELOPMENT
