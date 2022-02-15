# TravelModel
To run the trip-based travel demand model and process data requests for CLMPO

## Computer set-up
Install EMME, Cygwin, R, and Python 2.7, and set up the environmental variables

## Model running
1. Kate v1.0 cookbook

Model setup - Need to change the seedbank path if run with seed.

1.1 Navigate to the root directory of the iteration

`cd T:/Models/EMME/Metro/training_runs/iter8`

1.2 Make a copy of the Python setup script

`cp T:/Models/EMME/Metro/programs_v1.0_LCOG_120120/src/py/model_setup_kate1.0.py ./`

1.3 Run the script

`python model_setup_kate1.0.py`

## Data requests
### Lane miles by federal functional class

The federal functional class values are from the Lane County Road Centerlines (RLIDGeo.DBO.Road). Using [the nearest spatial join]() approach, the federal functional classes are added to the base year 2020 and future year 2045 links.
