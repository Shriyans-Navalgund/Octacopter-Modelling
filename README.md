# Octacopter-Modelling
## FDM Model of an Octacopter
### Model Limitations
- Phi and Theta are limited in the integrator to prevent inverted flight, i.e. values beyond +/- 180 and +/- 90 respectively are limited to max value and mdoel output is meaningless.
- No atmosphereic modelling currently, no density dependence of thrust.
- No wind modelling
- Drag force is a simple model and not corresponding to the actaul complex drag forces seen in propellers
- Thrust modeling is lookup table based, which is only relevant at psarticular conditions as provided by manufacturer. Refer thrustData
