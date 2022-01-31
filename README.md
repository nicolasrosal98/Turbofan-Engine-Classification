# Turbofan Engine Failure Prediction

Using an ensemble model to predict turbofan engine failure and quantify the potential impact of adopting machine learning in American Airlines's maintenance operations.
As an interesting side note, GAN-generated synthetic data was tested as a way to deal with unbalanced datasets. Refer to paper linked at the bottom for findings and dicussion.

*Authors*: Nicolás Rosal
<br /><br />

## Datasets

The datasets used can be found in NASA's [Prognostic Centre of Excellence] (https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/) datasets.
1. 'Turbofan Engine Degradation Simulation Data Set' was used for training, validation, and model tuning.
2. 'PHM08 Challenge Data Set' was used to test the optimal model against previously unseen data.

<br />

## Purpose

The purpose of this project was to build a machine learning model capable of identifying airplanes engines with a remaining useful life (RUL) of 20 days or less.
The potential uses of this model were identified as:

* Allow American Airlines to prepare for the maintenance activity at hand and perform repairs on time.
* Reduce tangible unplanned maintenance and downtime costs. 
* Reduce number of unplanned delayed and cancelled flights.

<br />

## Link to paper

Paper presented at 2021 Informs Annual Meeting: [click here] (https://github.com/nicolasrosal98/Turbofan-Engine-Classification/blob/main/Engine_failure_forecast_model_for_saving_the_operating_cost.pdf)
