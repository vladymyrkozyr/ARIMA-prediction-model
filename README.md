We worked with dataset provided by FF (see csv file in attachment) which consists of system usage data (cpu, memory, network etc.) for one month in 5-minute interval.

For our prediction model we chose ARIMA from python library which allows you to predict (extrapolate) data for the given previous data points.
The model from the attached screenshots is trained on the first 20 days of the month and tested on 10 last months.

Blue – real data
Red – predicted data