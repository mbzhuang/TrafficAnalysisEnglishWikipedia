# Traffic Analysis of English Wikipedia Website

### About the project
The goal of this project is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from Jan 1st, 2008 through Sep 30th, 2017. Wikipedia traffic from two different Wikimedia REST API endpoints are acquired through their respective API, combined into a single dataset, and finally visualized to show both the mobile and main site tranffic change from 2008 to 2017.

##### License of source data
API

Pagecounts: documentation, endpoint

Pageviews: documentation, endpoint

Both are licensed under the CC-BY-SA 3.0 and GFDL licenses.

See https://www.mediawiki.org/wiki/REST_API for background and details.

Wikimedia's Terms of Use and Privacy Policy

##### Steps of the project
* Data aquisition
  Special Note: Pageview API excludes spiders/crawlers, while data from the Pagecounts API does not.
* Data processing
  final data set
* Data analysis

##### Organization of the project

The project has the following structure:

```
TrafficAnalysisEnglishWikipedia/
  |- JSON_Data/
     |- pagecounts_desktop-site_200801-201607.json
     |- pagecounts_mobile-site_200801-201607.json 
     |- pageviews_desktop-site_201507-201709.json
     |- pageviews_mobile-web_201507-201709.json
     |- pageviews_mobile-app_201507-201709.json
  |- LICENSE
  |- PageviewAnalysis.ipynb
  |- PageviewPlot.png
  |- README.md
  |- en-wikipedia_traffic_200801-201709.csv
```
*This is an assignment for Data 512, University of Washington.

