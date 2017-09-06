# data_news.github.com
### 2017_data_news_competition_works_dydata
The repository introduces how to **visualize geographic data** in _the 2017 data news competition_.
The theme of competition is **Chinese folk custom** which is one of Chinese Intangible Cultural Heritage items.
So don't be strange about the data and diagram.
I apply two methods to implement the **spatial visualization**,including:
1. [Basemap](http://matplotlib.org/basemap/):The matplotlib basemap toolkit is a library for plotting 2D data on maps in Python
2. [Mapbox](https://en.wikipedia.org/wiki/Mapbox):Mapbox is a large provider of custom online maps for websites
## Basemap
There are 4 steps to visualize spatial data through _Basemap_.Proceed as follows:
- **collecting**: the source data comes from the website called _“The intangble cultural heritage in China”_.
- **preprocessing**：organize source data, delete useless information, simplify data set.
- **Geocoding**：transform a postal address to a numerical location.
- **visualizing**：take advantage of Basemap's function, loading _.shp_ file -> initializing map -> adding attributes
###### [Basemap-Ipython-Demp](https://github.com/Bingohong/data_news.github.com/tree/Static_Map_Basemap) in _Static_Map_Basemap_ Branch.

## Mapbox
###### [Mpabox-Demo](https://bingohong.github.io/data_news.github.com/China_itangible_cultural_heritage.html) in _gh-pages_ Branch

## My work called [**_《时空中的民俗》_**](http://www.dydata.io/article/p/897485299022766080)
I have no idea about how to deploy _.html page_ at first, so I had to screenshot the interactive map.It presents all aspects of my thinking about the _"Intangible Cultural Heritage"_ theme.

### Welcome! share your innovation about spatial visualization.
