# LSTM-Time-series-prediction---heating-degree-days
### Comparing two ML models to predict how many hours should/could heating be on in different buildings/places if temperature is below 15.5.

Dataset I have chosen for this assignment was downloaded from https://www.degreedays.net/. I chose Dublin Airport weather station, chosing reference point of **15.5** degrees Celzius (most common border temperature to decide when the heating is required or not). I have also included base temperatures nearby (getting range between 12.5 and 18.5 degrees).

*HDD* or *heating degree day* corresponds to sum of the number of hours when the outside temperature was below chosen border temperature (15.5) which is used to predict heating demand.

For example, on 19/06/2020, there was 2.6 hours (in total) when the outside temperature was below 15.5. That would indicate termal demand for those 2.6 hours (at least).

##How to Choose a Machine Learning Model

1. Collect data 
2. Check for anomalies, missing data and clean the data 
3. Perform statistical analysis and initial visualization 
4. Build models 
5. Check the accuracy #
6. Present the results
