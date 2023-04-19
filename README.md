# Solar-Generation-Forecasting-with-Transfer-Learning
**Master's Thesis**

This dissertation focuses on the development of pretrained Convolutional neural networks which can efficiently forecast solar energy production. More specifically, an investigation takes place concerning the ability of these pretrained models to be more efficient than models which are trained with small volumes of data.

In other words, neural networks are trained on a large timeseries dataset with solar and weather data from several European countries and then make predictions firstly for the dataset’s countries and then for countries with a few data. The experiments resulted in three deep neural network architectures which are mainly composed of Convolutional and Dense layers and which were compared with 4 efficient baseline approaches: NBEATS, Exponential Smoothing, Theta Method and a CNN architecture.

All of the three pretrained neural networks outperform all of the four baselines in predictions for both known and unknown countries data. The current repository presents the main parts of the thesis implementation but several parts from the phases of pretrained models' development, models' hyper-tuning and baselines' experiments are missing.

**his thesis has been submitted to Data Science and Advanced Analytics (DSAA) 2023  Conference**
