# Distribution Electric Field

## Radiation Pattern of the Microstrip Patch Antenna

This script has focused on the creation of polar and rectangular plots of ration pattern of higher-order mode for MPAs resonators.
The scriptcode have used the far field equation of electric component utilized on this reference thesis [^1].

#### Radiation Pattern of the TM<sub>01</sub> Mode
![TM01_polar_plot_W_60_L_60](https://github.com/heltonbernardo/distribution_field/assets/161172047/37487cc2-5039-4cff-8a2d-48e0e1168334)

#### Radiation Pattern of the TM<sub>02</sub> Mode
![TM02_polar_plot_W_60_L_60](https://github.com/heltonbernardo/distribution_field/assets/161172047/4b83e25b-046b-4c69-96a4-03409a994074)

#### Radiation Pattern of the TM<sub>03</sub> Mode
![TM03_polar_plot_W_60_L_60](https://github.com/heltonbernardo/distribution_field/assets/161172047/8bc9d073-5ec6-4edb-a56e-aa04f338261d)

#### Radiation Pattern of the TM<sub>05</sub> Mode
![TM05_polar_plot_W_60_L_60](https://github.com/heltonbernardo/distribution_field/assets/161172047/5d48a814-3e3e-429f-a7c0-78802275416e)

For compute resonance frequency, we have used to function `high_order_tm(m,n,L,W,e_r,h)` which need to calculate cavity model effects.
This function was set up in one of the my `resonance_frequency` repositories done.

[^1]: Z. Ahmed, "TM<sub> mn <\sub> Mode Rectangular Patch Antennas with Improved Radiation Characteristics," Ph.D. thesis, Faculty of Eng., 
Capital Univ. of Technology, Islamabad, 2021.

