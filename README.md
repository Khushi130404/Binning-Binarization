# Binning-Binarization

This repository demonstrates the concepts of binning and binarization using the Titanic dataset. It explores the impact of numerical encoding on the results and compares the outcomes with and without applying numeric encoding techniques. Visualizations are provided to analyze the transformations and their effects on the dataset.

## Features
- Binning:- Dividing continuous numeric features into discrete bins.
- Binarization:- Converting numeric values into binary values based on thresholds.
- Comparison:-
  - With numeric encoding: Analyze the transformations after encoding categorical variables into numeric form.
  - Without numeric encoding: Observe the effects directly on raw numerical features.
  - Visualization: Generate graphs to visualize the effects of binning and binarization on the dataset.

## Dataset
The project uses the Titanic dataset, with the following primary features:-
- Age: Continuous numeric feature representing passenger age.
- Fare: Continuous numeric feature representing ticket fare.
- SibSp: Discrete numeric feature for the number of siblings/spouses aboard.
- Parch: Discrete numeric feature for the number of parents/children aboard.
- Survived: Target variable indicating survival (0 = No, 1 = Yes).

## Dependencies
Ensure you have the following Python libraries installed:-
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

