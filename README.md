# Jobs.cz scraper

Jobs.cz scraper works as the name suggests. There are a couple of variables, which are crucial for the whole script. Keywords list is a list of words you want the found job titles contain. Blacklist list is a list of words you do not want the found job titles contain. Location is a city of your interest.

Note, the script is written with intend to be used every day, that is why the date from which you want the offers to be shown is set for yestarday. Small adjustments are needed for an arbitrary date.

## Requirements

In order to run this scripts you need these python modules

```bash
numpy
requests
BeautifulSoup
openpyxl
```

## Author
Martin Groman, 2020

## License
[MIT](https://choosealicense.com/licenses/mit/)
