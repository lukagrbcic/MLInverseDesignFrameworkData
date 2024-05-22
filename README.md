# Efficient Inverse Design Optimization through Multi-fidelity Simulations, Machine Learning, and Boundary Refinement Strategies

Data for the manuscript "Efficient Inverse Design Optimization through Multi-fidelity Simulations, Machine Learning, and Boundary Refinement Strategies" by Luka Grbcic (LBNL), Juliane Müller (NREL), and Wibe Albert de Jong (LBNL), 2024.

LBNL - Lawrence Berkeley National Laboratory

NREL - National Renewable Energy Laboratory
_______

DATA DESCRIPTION -- Airfoil Inverse Design (AID)
_________

**AID_Cp_targets** -- containts pressure coefficient target values for the RAE2822 and NACA2410 airfoils. First row both files represents the normalized x coordinate, while the second are the Cp values.
	
**AID_ML_model_data** -- containts the data needed to train the ML models. Each row in the x.txt file are the B-Spline coefficients that represent an airfoil shape. Cpmin.txt is the file that contains the minimum pressure coefficient for each shape in x.txt. B-spline coefficients are the inputs to trains the ML model, while the Cpmin values are the output.

_______

DATA DESCRIPTION -- Scalar Field Reconstruction (SFR)
_________


SFR_s_targets

SFR_ML_model_data

SFR_OpenFOAM_cases
