# Zanzibar I3 Model
Malaria transmission model for studying imported, introduced and indigenous cases in low transmission settings.

Copyright (C) 2021 Swiss Tropical and Public Health Institute

This malaria model is free software; you can redistribute it and/or modify it under the terms of version 2 of the GNU General Public License as published by the Free Software Foundation.

## Data
This folder contains two files:
* parameters.csv: This contains the fixed parameter values derived from the RADZEC study and other sources.
* param_100.csv: This contains 100 draws from various parameter distributions based on the data from the RADZEC study. This was used for estimating the uncertainty in the final malaria prevalence reached after 40 years, based on the uncertainty in the input parameters and the stochasticity of the model.

## Interventions
This folder contains *n* files:
* interventions.csv: This contains the fixed parameter values derived from the RADZEC study and other sources.

## I3 Model
This folder contains the files used to simulate various combinations of interventions.
* i3_model.py: Base model in which all RCD-related interventions, treatment of travellers and transmission reduction on Zanzibar are included
* i3_model_betared_MT.py: Treatment on mainland Tanzania also simulated
* i3_model_param.py: Testing parameter uncertainty
* i3_model_varying_tau.py: Testing a fixed vs varying targetting ratio



## Sensitivity Analysis



