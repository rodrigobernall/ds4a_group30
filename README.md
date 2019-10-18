# Dataton project - Group 30 (DS4A Colombia 2019)

## Folder structure

- models: contain all reutilizable functions such as predictors and functions. 
- Scripts : where we are going to store notebooks
- Output : plots, table and logbook of the project 
- Input : All data sources


## Original data

To load the CSV datasets use the following syntax (either from Google Colab or from a local Jupyter notebook).

	dataset = pd.read_csv(url)

For the compressed datasets (GZ), use this command:

	dataset = pd.read_csv(url, compression='gzip')

This will uncompress the file automatically and load the csv within.

The urls are:

uber_trips_2014.csv.gz

	url = 'https://www.dropbox.com/s/b09qj0x8749pu36/uber_trips_2014.csv.gz?dl=1'

uber_trips_2015.csv.gz

	url = 'https://www.dropbox.com/s/nuy53h611y1j0b9/uber_trips_2015.csv.gz?dl=1'

mta_trips.csv.gz

	url = 'https://www.dropbox.com/s/6couhvy9xzvmuqy/mta_trips.csv.gz?dl=1'

green_trips.csv.gz

	url = 'https://www.dropbox.com/s/z1a8igph8cwpmcx/green_trips.csv.gz?dl=1'

yellow_trips.csv.gz

	url = 'https://www.dropbox.com/s/3itjm0thz0m3031/yellow_trips.csv.gz?dl=1'

demographics.csv

	url = 'https://www.dropbox.com/s/8gys15vzjpd1ibu/demographics.csv?dl=1'

geographic.csv

	url = 'https://www.dropbox.com/s/6s162261bj0i1za/geographic.csv?dl=1'

weather.csv

	url = 'https://www.dropbox.com/s/0acrufa25h3x3a4/weather.csv?dl=1'

zones.csv

	url = 'https://www.dropbox.com/s/pjovxyr8w6x6y5x/zones.csv?dl=1'
	

## Processed data (includes NTA of pickup and dropoff)

uber_trips_2014_nta.csv.gz
	
	url = 'https://www.dropbox.com/s/za6yp2mz6p560o1/uber_trips_2014_nta.csv.gz?dl=1'
	

green_trips_nta.csv.gz

	url = 'https://www.dropbox.com/s/7ixw7pe46q3theo/green_trips_nta.csv.gz?dl=1'
	
yellow_trips_nta.csv.gz

	url = 'https://www.dropbox.com/s/k4amamqkqf7ap92/yellow_trips_nta.csv.gz?dl=1'

## Project questions

| ID | QUESTION                                                                                                        | COMMENTS                                                                                                                                   |
|----|-----------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| 1  | In what locations and to what extent did we displace taxicabs? And competence between green and yellow taxis?   | Do a heatmap in each dataset with geographic information. ‘Draw the dataset over a map.’Everyone starts with yellow until someone gets it. |
| 2  | What are the times and areas with the greatest demand for transportation?                                       | Order the geographic information in polygons.                                                                                              |
| 3  | Who are more affected by the rain (and the wheather in general): Uber, taxicabs, metro?                         | Create indicators. Compute passengers per hour in dry days and rainy days.                                                                 |
| 4  | Where and when is there a shortage of metro routes?                                                             | Negative correlation between taxi rides and metro stations.                                                                                |
| 5  | What is the proportion of income people spend on transportation per borough/neighborhood and area?              |                                                                                                                                            |
| 6  | What are the routes with the largest demand?                                                                    | Depends on how sparse the trip information is.                                                                                             |
| 7  | Where and when do traffic jams concentrate and what route changes would be applicable to improve the situation? |                                                                                                                                            |
