# Sad Songs: Feeling lonely around the globe 

## Spotify listening trends and COVID-19 lockdown patterns

### The core concept of the module-1 project is to use Spotify's API and Spotipy to analyze the general "mood" of the top charts at the country level. Next, we want to look at the stringency of national policy responses to COVID-19, which we took from the Oxford Government Response Tracker. We wanted to see if the general "mood" of the music streamed was influenced by COVID-19 stay at home measures. 


**Project by Thomas & David & Kate** 

*In this repo you will find:*
 * Jupyter Notebook: "spotify_api.ipynb" with all data wrangled with Spotify API and preliminary analysis
 * Jupyter Notebook: "ox_covid_test.ipynb" with the data taken from Oxford dataset and cleaned/subsetted to show stay at home requirements
 * Jupyter Notebook: "together_test.ipynb" that puts together our COVID and Spotify dataframes for more plotting and analysis
 * All .csv files with imported data and the dataframes we made in Folder "data"
 * Folder "oxford_original_data" with the Oxford database
 * Folder "Spotify_regional" with all the country charts (Top 200 songs, April 2019-September 2020)
 * Folder "Misc. extra" with non-essential files 
 ...
 
 *If you want to replicate our results:*
  * First run the "spotify_api.ipynb" and the "ox_covid_test.ipynb" notebooks for wrangle the data to use for analysis
  * Then you can run the "together_test.ipynb" notebook to combine the data and do a comparative analysis
  * Don't forget to download/upload the .csv files for comparative analysis
  
**Data Sources**

*Data Source 1: Data from Spotify API*
 * link to Spotify charts: https://spotifycharts.com/regional

*Data Source 2: Database from OxCGRT re: policy responses to COVID-19*
 * link to Oxford data: https://covidtracker.bsg.ox.ac.uk/
 * https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker#data
 * https://covidtracker.bsg.ox.ac.uk/about-api
 * https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker
 * 

**Countries of Focus**

* United States
* Brazil
* Italy
* Singapore
* South Africa

**Breakdown of Tasks**

 * Wrangle music data from Spotify API (Thomas:)
 * Identify and isolate the specific Spotify data we want for our analysis and save .csv files
 * Clean and structure Spotify data 
 * Created Spotify-specific plots (valence over time, dancability over time, streaming patters of Top 10 charts)
 * Find and download database with COVID policy responses (Kate:)
 * Identify and isolate the specific data we want for our analysis and save .csv files
 * Clean and structure Oxford data
 * Created Oxford-specific plots (stringency of stay at home requirements over time per country, comparison of 5 countries, Italy 2019-2020 data to compare to streaming patterns)
 * Putting it all together (David:)
 * Harmonize the dataframes from Spotify and Oxford .csv files to compare trends
 * Clean and re-format to ensure the primary key worked for both datasets 
 * Merge dataframes together to compare
 * Plot country specific comparisons of the Spotify and Oxford data
