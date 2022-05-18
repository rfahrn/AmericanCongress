# AmericanCongress

## Running speech complexity analysis
Download the data from [here](https://data.stanford.edu/congress_text#download-data) and unpack it into a folder called `hein-daily` in the root of this project's directory. 
Then run the `ReadRawFiles` notebook which will generate new files in the folder `preprocessed_data`. 
Consecutively, the `SpeechComplexityAnalysis` script can be run and it will save all plots in the `plots` folder. 



## For running the BERTopic Model
first make sure to download the data and upload it to google drive, then use the google colab, open the notebook and change the paths to your data, then use the GPU of google colab and go through the notebook.
