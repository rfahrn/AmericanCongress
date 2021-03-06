# AmericanCongress

## Running speech complexity analysis
Download the data from [here](https://data.stanford.edu/congress_text#download-data) and unpack it into a folder called `hein-daily` in the root of this project's directory. 
Then run the `ReadRawFiles` notebook which will generate new files in the folder `preprocessed_data`. 
Consecutively, the `SpeechComplexityAnalysis` script can be run and it will save all plots in the `plots` folder. 

## Running geographical analysis
To perform this analysis you don't need to download anything, everything should be in the appropriate folders. The data for the map can be found in the "gpd_data" folder. You can just run the script and it should automatically save the pictures in the "pictures_party_map" folder and the gif in the "gif" folder.

## For running the BERTopic Model
first make sure to download the data and upload it to google drive, then use the google colab, open the notebook and change the paths to your data, then use the GPU of google colab and go through the notebook.

## For running the Cluster analyse
To perform clustering by party affliation run the Congressional_clustering.ipynb. You can run it on the raw data (SpeakerMap, byparty_2gram, byspeaker_2gram, partisan_phrases from 097 to 114 aswell as topic_phrases)  to perform clustering this takes 5 minutes or load in the pre run data from year_issues_partisan (1).pkl to make the plots. To perform clustering by bigram topic run the Issue_clustering.ipynb you can run the program on the data which takes aprox 2 hours or load in the pre run data year_issues_quad.pkl to make the plots. 
