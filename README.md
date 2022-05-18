# AmericanCongress

## Running speech complexity analysis
Download the data from [here](https://data.stanford.edu/congress_text#download-data) and unpack it into a folder called `hein-daily` in the root of this project's directory. 
Then run the `ReadRawFiles` notebook which will generate new files in the folder `preprocessed_data`. 
Consecutively, the `SpeechComplexityAnalysis` script can be run and it will save all plots in the `plots` folder. 

## Running geographical analysis
To perform this analysis you don't need to download anything, everything should be in the appropriate folders. The data for the map can be found in the "gpd_data" folder. You can just run the script and it should automatically save the pictures in the "pictures_party_map" folder and the gif in the "gif" folder.

## For running the BERTopic Model
first make sure to download the data and upload it to google drive, then use the google colab, open the notebook and change the paths to your data, then use the GPU of google colab and go through the notebook.
