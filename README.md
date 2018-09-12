# Kijiji-Scraper
Python 3 script that scrapes Kijiji ad information and outputs it in `.json` format


## Usage:

 Run `./Kijiji-Scraper.py -h` for usage instructions

## Example usage:

`$ ./Kijiji-Scraper.py -u 'https://www.kijiji.ca/b-bikes/city-of-toronto/c644l1700273r0.7?ad=offering&address=m5c2t6&ll=43.641210,-79.393892' -f bikes.json -v`

## Dependencies: requests and BeautifulSoup

```
conda install requests
conda install beautifulsoup4
```

## Bonus: load output in pandas

```
import pandas as pd

df = pd.read_json('bikes.json', orient='records')
```
