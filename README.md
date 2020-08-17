# Machine Learning with ADS-B

Machine learning regression of the latitude of aircrafts with an automatic dependent surveillance–broadcast (ADS-B) dataset.

## Background

The aircraft localization is essential for securing the airspace. Most of the Airplanes and all commercially used ones use the ADS-B, which is a broadcasting information dataset about the aircraft for surveilance purposes. The ADS-B is transmitted with 1090 MHz and can be received by any sensor, since it is not encrypted. Such a dataset is here provided by the OpenSky-Network.

This work is a revision of one of my academical practical courses on machine learning. In the making of this, a paper had been created which was restricted to 6 pages in length. This paper can be found in this github with the name 'Machine_Learning_with_ADS-B.pdf'. This paper also describes the work in detail. Some of the context is also given in the following as well as in the jupyter notebook code.

## Preprocessing Algorithm

The Data used for this work consists of two csv files. One about of the ADS-B signals and a second one of the sensors that helped to receive the ADS-B signals.  The jupyter notebook python file 'preprocessing.ipynb' requires those two datasets to be placed in a folder called 'data'. Finally, this code creates a new csv file of the preprocessed results of the data.

## Learning Algorithm

The learning algorithms in 'learning.ipynb' implements a random forest and a support vector regressor. Those algorithms are then compared together with a dummy mean estimator as well as a simple decision tree model. The learning is executed on the preprocessed data.

## Contribution 

The code and the paper had been written by Jan Zimbelmann.
