# DATA-PHYS-3888
University of Sydney DATA3888/PHYS3888 Capstone Brain Project. This project utilised a Spikerbox to record Electrooculography and report reaction time. The product is written in python and involves data collection, event extraction, event classification and live streaming. The final GUI was a screen with two tiles, where one will light up and the time taken to look in the right direction is returned. This is repeated 5 times and an average reaction time will be outputted. 

# Packages:
## Python (version 3.9.7):
* CSV
* Freegames
* Matplotlib
* Numpy
* Pandas
* Pickle
* Random
* Scipy
* Serial
* Sklearn
* Statistics
* Time
* Turtle

# Instructions:
* Run(Data collection code in Project report appendix code 1) to record raw data and save as a .csv file
* Import the raw data into (Event extraction code in Project report appendix code 2) and run to extract events and save as a .csv file
* Import the extracted event values into (Classifer code in Project report appendix code 3 SVM) and run to train an SVM machine learning model save as a .sav file
* Run (Appendix Figure 1 code) to evaluate the performance of the model
* Import the SVM model into (Final produce code in appendix code 4) and run to start the program
