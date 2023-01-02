# MiPace
VO2max Prediction via Machine Learning Algorithms

In sports physiology, VO2max, or maximal oxygen consumption, stands for the maximum amount of oxygen that an individual can utilize during high/maximal intensity of exercise, which has been one of the most reliable metrics to predict human performance in endurance sports. In general, the direct measurement of VO2max (in lab testing) provides the most accurate results. However, given limited time and resources, not everyone can have access to the sophisticated equipment that can conduct these tests. During the past few years, there have been numerous studies trying to build algorithms to predict VO2max, which we will briefly introduce in the related works section.
Moreover, as most of our group members are weekend warriors for different sports, we found out that Garmin watches have a special algorithm to predict VO2max based on an athlete’s running metrics during exercise without measuring the true oxygen uptake. 
Hence, with some available data in hand, we would like to predict a person’s VO2max based on different physiological parameters and hope to construct a prediction model that can beat Garmin’s algorithm.
To sum up, VO2max can help people measure fitness and health improvement over time. It is very helpful for athletes like runners to guide and evaluate their training by looking at VO2max. In this study, we hope to exempt people from the tedious process of visiting a lab or testing center to know the value of their VO2max; instead, people can measure simple static features by themselves and estimate their VO2max with our predictive model.  

mipace_preprocessing.ipynb contains the data preprocessing for cleaning, combining, and finalizng the dataset we want for prediction
models.ipynb is the main file for running machine learning predictions 

A google slide report can be found here: https://docs.google.com/presentation/d/1xVrEIdl_vg4pfXaY0_7kL0eD5yOwVU3B3dsfswG-GN4/edit#slide=id.p
