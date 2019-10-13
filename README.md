# Dataton project - Group 30 (DS4A Colombia 2019)

To load the CSV datasets use the following syntax (either from Google Colab or from a Jupyter local notebook).

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
