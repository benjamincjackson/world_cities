#### World cities information

This repository contains a parsed version of the world cities data
from here:

https://download.geonames.org/export/dump/cities15000.zip [1]

downsampled to cities with  population greater than 50,000, and to two columns - city name and ISO 3166 two-letter country code. To make `cities50000.tsv` from `cities15000.txt`, run:

`python3 parse_world_cities.py`


#### data from

1. http://www.geonames.org/
