# Crosstalk optical interferometers

This repository contains the data underlying the article "Crosstalk in image plane beam combination for optical interferometers" published in MNRAS. 

## File naming convention: 

The files in the data folder are named after the parameter configuration they represent. Alpha_1.5_Beta_2_Delta_0.5_Gamma_1_Tip_tilt_0.5_pixels_per_ro_80.0.csv for example is the run from the simulation for parameter values of α = 1.5, β = 2, δ = 0.5, γ = 1, T = 0.5 where the parameters have the same meaning as described in section 2.3 of the paper. 

pixels_per_ro represents how many pixels per Fried parameter the phase screen used in the run was simulated at. This value varies for runs with different values of α as the diameter of the pupil (in pixels) is held constant between simulation runs and so for worse seeing (larger α) the number of pixels/ro decreases. 

## Data description: 

The files in the data folder contain 20 independent measurements of the visibility as a function of spatial frequency, where each of the 20 visibility measurements are calculated for an ensemble of 500 PSFs as described in section 2.5 of the paper. 

The first column lists the spatial frequency at each point the visibility was sampled at. The shape of the visibility curves can be understood from figure 3 of the paper. As the pupils were separated by four times their pupil diameter (as described in section 2.6 of the paper) the peak of the visibility occurs at a spatial frequency of four, except for the runs with β > 4 for which the pupils are separated further. 

Note these data are of the visibility, not the visibility squared as presented in the paper. 

## Usage: 

If this data was helpful for your research, please cite the paper associated with this work, available here: INSERT LINK 

## Contact: 

If you have any questions/comments please get in touch via d.j.mortimer@exeter.ac.uk, I'd love to hear from you!
