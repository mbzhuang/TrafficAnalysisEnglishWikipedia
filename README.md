# Traffic Analysis of English Wikipedia Website

### About the project
The goal of this project is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from Jan 1st, 2008 through Sep 30th, 2017. Wikipedia traffic from two different Wikimedia REST API endpoints are acquired through their respective API, combined into a single dataset, and finally visualized to show both the mobile and main site tranffic change from 2008 to 2017.

#### License of source data
##### API

Pagecounts API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts), [endpoint](https://wikimedia.org/api/rest_v1/#!/Pagecounts_data_(legacy)/get_metrics_legacy_pagecounts_aggregate_project_access_site_granularity_start_end)) provides access to desktop and mobile traffic data from January 2008 through July 2016.

Pageviews API ([documentation](https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews), [endpoint](https://wikimedia.org/api/rest_v1/#!/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end)) provides access to desktop, mobile web, and mobile app traffic data from July 2015 through September 2017.

Both are licensed under the [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) and [GFDL](https://www.gnu.org/copyleft/fdl.html) licenses.

##### Wikimedia's [Terms of Use](https://wikimediafoundation.org/wiki/Terms_of_Use) and [Privacy Policy](https://wikimediafoundation.org/wiki/Privacy_policy)

#### Steps of the project
* Data aquisition
  Special Note: Pageview API excludes spiders/crawlers, while data from the Pagecounts API does not.
* Data processing
  final data set
* Data analysis

#### Organization of the project

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

