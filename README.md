# SPIKE-Spiking-Pattern-Investigation-for-Kepler-Exoplanets---SciFair-2025-26
Question: Can a spiking neural network (SNN) accurately detect exoplanet transits from Kepler light-curve data? If so, is it possible to find new exoplanets?
Hypothesis: If a spiking neural network is trained on Kepler light-curve data in Python, then it will be able to identify exoplanet transits because SNNs can capture patterns over time by mimicking how neurons process signals.
Engineering Goal: Design and train a spiking neural network model that can process Kepler telescope light-curve data and identify whether a star’s brightness dip corresponds to a potential exoplanet transit. The goal is to show that neuromorphic, event-based learning can efficiently handle sequential astrophysical data.

Procedure:
Download Kepler light-curve data from Kaggle (NASA Dataset)
Clean and prepare the data for analysis (normalize, remove trends)
Label examples as transit or no-transit
Convert light curves into spike patterns for the SNN
Build and train the python SPIKE model using the training dataset
Test the model on light curves that have already been found.
Analyze results (accuracy, precision, spike visualizations)
Compare predictions to known exoplanets in catalogs
Conclude how well SPIKE detects exoplanets

No harmful or dangerous substances/organisms/tools will be used in this project.

CREDITS TO ASHISH K. S. ARYA FOR THE ORGININAL PROJECT MODEL ON KAGGLE: https://www.kaggle.com/code/ashish21/exoplanet-detection-using-spiking-neural-networks/notebook
DATASET ON KAGGLE: https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data
