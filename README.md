# Visualizations

My dataset is originally from Kaggle (https://www.kaggle.com/datasets/NUFORC/ufo-sightings?resource=download) but uses data that was scraped, geolocated, and time-stamped using NUFORC data by an individual named Sigmond Axel (https://github.com/planetsig/ufo-reports). 
I have no connection to either individual but merely found it by googling. Note that Sigmond has provided a scrubbed and a complete file. I am using the scrubbed file, which has already handled some date formatting and cleaning. 
NURORC is National UFO Reporting Center and is a non-profit founded in 1974 that is "dedicated to the collection and dissemination of objective UFO data." 

Data is for years 1965 through 2014. You will have to specify a start year, a final year, and a focus year (for the detailed charts).

Please ensure that start_year <= focus_year <= final_year, otherwise .... you're gonna have a bad time. Plus the code won't work.
