# AeroMetrics - Airport Efficiency Ratings
### Overview
`
The goal of the AeroMetrics project is being able to measure an airport's efficiency based upon handling traffic with as less delay as possible, and using it to cluster airports, analyze what makes them efficient, provide feedback to the airports, and information to the public.
`
### Libraries used:
- Plotly
- Pandas
- Seaborn
- Matplotlib
- Math
- Random
- Numpy

`Running the main file on your own computer might not be convenient and potentially too time consuming due to the large raw files used in this study. In order to have the smoothest experience, we highly recommend accessing our google collab jupyter notebook through the following linked folder:`

[Link to google drive folder containing raw data and final submission file](https://drive.google.com/drive/folders/1h3rHHGbOTcc6dEzsedYLwH8wtWmqdlFB?usp=sharing)

*Ideally, you should not have to run any cells yourself and be able to view the results of each cell we've run through the collab notebook.*
**Please make sure to authenticate using your TAMU email. Instructor and TA has been added to the drive. Please let us know, if someone else wants the access to drive. Please email us at uak4676@tamu.edu**

##### Please continue reading below for details regarding our process.
##### Cleaning and Preprocessing
- Fetched and loaded data from BTS website.
- Cleaned data by
    - removing unnecessary rows before 2019
    - removing columns that didn't affect airport efficiency based on our findings
    - replacing 'NaN' values with logic / interpolated values
- Preprocessed data by
    - forming a formula to measure efficiency based on certain factors
    - creating new columns needed for said factors that were not present in the original dataset
        - percentiles, rates, and positions
- Validating the formula
    - created several charts comparing different factors with the generated scores to confirm the formula was providing desired and sensible results.

##### Clustering...

##### Visualization
- The visualization was obtained from the airport data and the ranked and processed flight delay stats
- This visualization was possible using plotly
- Mapbox API is begin accessed using ploty to create visualization
- Open Street Map is being used in Map box API because of following info
    - Open Source Map.
    - Easy to manipulate.
    - Good Coloring Scheme with our model.
    - Great Details with frequent updates, because of open source nature.
