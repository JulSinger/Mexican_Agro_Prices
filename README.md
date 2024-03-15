# Mexican Agricultural Prices - Every Product and Market

<p align="justify"> The associated Jupyter Notebook for this repository, contains a data scraping function and a simple data analysis for Avocado prices in Mexico. 
The web scraping function scraps the National System of Market Information (SNIIM in Spanish) which previously contained a search engine
to get prices information for an specific Agricultural Product, Market and Period. The results were not downloadable, making it very difficult to analyze the data. The function contained in the notebook, 
allows to download all the data (all time data) for an specific product and market. </p>

The following graph (code in notebook) is an example of the prices information retrieved from the web:
![Avocado_price](https://github.com/JulSinger/Mexican_Agro_Prices/assets/144071550/19680784-c001-482a-8433-0bc35dd9d6c9)

Additionally, we can make a plot to know which Mexican State was the main supplier for Avocado between the years 2010-2023:
![Avocado_origin](https://github.com/JulSinger/Mexican_Agro_Prices/assets/144071550/0c487714-d2b9-45b9-b1f0-d412ac003331)

<p align="justify">Since the function downloads all the available days with price information, there may be no changes in price between some periods. 
Hence, we transform the data frame to contain only dates with different prices to achieve a smoother plot:</p>

![Avocado_price_transform](https://github.com/JulSinger/Mexican_Agro_Prices/assets/144071550/083d4abe-2af8-41da-9faa-80921567d13a)
