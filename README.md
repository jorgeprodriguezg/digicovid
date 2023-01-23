# digicovid

Code used for Rodríguez, J.P., Aleta, A., Moreno, Y., "Digital cities and the spread of COVID-19: characterizing the impact of non-pharmaceutical interventions in five cities in Spain", [arXiv preprint](https://doi.org/10.48550/arXiv.2212.06659), 2023

The code uses the open-source software [COVASIM](https://github.com/InstituteforDiseaseModeling/covasim)

The files included in this repository reproduce the simulation of the first and second waves in Zaragoza, including non-pharmaceutical interventions.

+ zaragoza_notrun.sim is a simulation file including data: official time series of number of infected and deaths, age and sex of each considered individual and contacts in six interaction layers (home, school, university, work, nursing homes and community).

+ zaragoza_wv2.ipynb is a Jupyter notebook that loads zaragoza_notrun.sim and runs it with the calibrated parameters.
