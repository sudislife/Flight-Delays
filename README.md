# Flight Delays Analysis
This project uses the Flight Delays dataset from Kaggle ([link](https://www.kaggle.com/competitions/flight-delays-fall-2018/data)). This data consists of flight delays in the year 2018 and consists of attributes such as the date, departure time, unique carrier, origin, destination, and distance between origin and destination airports.

## Data Exploration
### What does the data distribution look like?
![Data Distribution (If you see this, please contact me and let me know)](https://raw.githubusercontent.com/sudislife/Flight-Delays/main/ReadmePlots/Data%20Distribution.png)

The data seems to be clearly have a lot more data points for non delays.

### What does the distribution of the different carriers look like?
![Airline Carrier Distribution (If you see this, please contact me and let me know)](https://raw.githubusercontent.com/sudislife/Flight-Delays/main/ReadmePlots/Airline%20Carrier%20Distribution.png)

The airline carrier names are given in the legend of the pie chart in descending order of distribution.

WN seems to have the highest number of data points contributing to 15% of the data. Airline carriers from AA down to FL have almost equal distributions, while DH and the airline carriers below it contribute less than 1% each to the data distribution.

### Are the delays related to the airline carriers?
![Number of Delays by different Airline Carriers (If you see this, please contact me and let me know)](https://raw.githubusercontent.com/sudislife/Flight-Delays/main/ReadmePlots/Number%20of%20Delays%20by%20different%20Airline%20Carriers.png)

Our analysis indicates that [Southwest Airlines](https://simpleflying.com/southwest-airlines-wn-code-explanation/) (WN) has the highest number of both delayed and on-time flights

### Is distance between origin and destination a contributing factor to the delays?
![Number of Delays vs Distance (If you see this, please contact me and let me know)](https://raw.githubusercontent.com/sudislife/Flight-Delays/main/ReadmePlots/Number%20of%20delays%20over%20flight%20distance.png)

Shorter distance flights seem to show a higher delay trend as shown in the plot above. However, as seen in the box plot above the histogram, since most of our data points fall within this distance range, this trend might be influenced by data distribution rather than a true correlation.