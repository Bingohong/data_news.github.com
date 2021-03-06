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
- Step1-**collecting**: the source data comes from the website called _“The intangble cultural heritage in China”_.
[_非遗名录-各批次_](https://github.com/Bingohong/data_news.github.com/blob/Static_Map_Basemap/%E9%9D%9E%E9%81%97%E5%90%8D%E5%BD%95-%E5%90%84%E6%89%B9%E6%AC%A1.xlsx) & [_中国34座省会城市坐标_](https://github.com/Bingohong/data_news.github.com/blob/Static_Map_Basemap/%E4%B8%AD%E5%9B%BD34%E5%BA%A7%E7%9C%81%E4%BC%9A%E5%9F%8E%E5%B8%82%E5%9D%90%E6%A0%87.xls)
- Step2-**preprocessing**：organize source data, delete useless information, simplify data set.
[_非遗名录-汇总_](https://github.com/Bingohong/data_news.github.com/blob/Static_Map_Basemap/%E9%9D%9E%E9%81%97%E5%90%8D%E5%BD%95-%E6%B1%87%E6%80%BB.xlsx)
- Step3-**Geocoding**：transform a postal address to a numerical location.[_GEOCEDING_IPYTHON_](https://github.com/Bingohong/data_news.github.com/blob/Static_Map_Basemap/STEP-3-Geocoding.ipynb)
- Step4-**visualizing**：take advantage of Basemap's function, loading _.shp_ file -> initializing map -> adding attributes.[_VISUALIZING_IPYTHON_](https://github.com/Bingohong/data_news.github.com/blob/Static_Map_Basemap/STEP-4-Visualizing.ipynb)
###### [Basemap-Ipython-Demo](https://github.com/Bingohong/data_news.github.com/tree/Static_Map_Basemap) in _Static_Map_Basemap_ Branch.

## Mapbox
You can take advantage of [_mapbox manual_](https://www.mapbox.com/help/studio-manual/) to finish your first map.For all of us, it is sample for us to creat a static map with [_tutorials_](https://www.mapbox.com/help/studio-manual-tutorials/), all you need it just follows the step-to-step.But a interacitve map have to utilize coding script with [_Map GLJS_](https://www.mapbox.com/mapbox-gl-js/api/).My mapbox demo follows:
###### [Mapbox-Demo](https://bingohong.github.io/data_news.github.com/China_itangible_cultural_heritage.html) in _gh-pages_ Branch

## My work called [**_《时空中的民俗》_**](http://www.dydata.io/article/p/897485299022766080) in dydata websites.
I have no idea about how to deploy _.html page_ at first, so I had to screenshot the interactive map.It presents all aspects of my thinking about the _"Intangible Cultural Heritage"_ theme.The interactive map can click [_Mapbox-Demo_](https://bingohong.github.io/data_news.github.com/China_itangible_cultural_heritage.html).

### Welcome! share your innovation about spatial visualization.
