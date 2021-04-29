# IBM-Applied-Data-Science-Capstone

### Introduction
This is the capstone project for the IBM Data Science Professional Certificate. In this project, I will be exploring "coffee shops" in Toronto area. I made a hypothesis that there are already many coffee shops in downtown Toronto, so it might be a good choice for future coffee shop owners to open a new store in other areas for more opportunities. As coffee shops are highly competitive, this project will serve as a good reference for entrepreneurs before they decide where to open their future shop.


### Business Problem
The goal for this project is to find areas with less coffee shops so that future coffee shop owners will have more opportunities to succeed. By using the techniques I learned from the course, I hope that I can help entrepreneurs answer this question: which area is least competitive and will be a great choice to open a new coffee shop?

### Who will be interested
Future coffee shop owners who are deciding the location for their future shop.

### Data Sources
1. List of neighborhoods in Toronto, Canafa (https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M)
2. Latitude and Longitude of the neighborhoods (a csv file provided by IBM)
3. Venue data for coffee shops in Toronto

### Method
1. I will be using BeautifulSoup to scrap data of neighborhoods in Toronto from a wikipedia page and save it as a Pandas dataframe.
2. Next, I will merge the table with latitude and longitude data to get a more informative table.
3. I will use Foursquare API to get venue data of coffee shops in Toronto
