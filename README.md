# google-chart-offline
I record google chart and find it will be local if you change several keywords in the two load.js. I upload it here but dont use it in your application because it is out of the license of google chart.

-----
## Setup
### Record Network Activity
Find files initiated by `loader.js`, save them to the appropriate (JS/CSS) subfolder in `offlineSaving`.
<img src="saveas.png">

### Edit Main Loader Script
Network Activity shows as initiated by `(index)`. Live version would be found at `https://www.gstatic.com/charts/loader.js`.
- Replace `https://www.gstatic.com` with `.`
- Change current version to "offlineSaving"
<img src="replace2.png">
<img src="replace3.png">

### Edit Versioned Loader Script
Network Activity shows as initiated by `loader.js`. Live version would be found at `https://www.gstatic.com/charts/46.2/loader.js`.
- Replace `https://www.gstatic.com` with `.`
<img src="replace1.png">

-----
## Other Info
### Package Reference
| Chart Type | Package Name |
| --- | --- |
| Annotation Charts | annotation |
| Area Charts | corechart |
| Bar Charts | corechart |
| Bubble Charts | corechart |
| Calendar Charts | calendar |
| Candlestick Charts | corechart |
| Column Charts | corechart |
| Combo Charts | corechart |
| Diff Charts | corechart |
| Donut Charts | corechart |
| Gantt Charts | gantt |
| Gauge Charts | gauge |
| GeoCharts | geochart |
| Histograms | corechart |
| Intervals | corechart |
| Line Charts | corechart |
| Maps | map |
| Org Charts | orgchart |
| Pie Charts | corechart |
| Sankey Diagrams | sankey |
| Scatter Charts | corechart |
| Stepped Area Charts | corechart |
| Table Charts | table |
| Timelines | timeline |
| Tree Map Charts | treemap |
| Trendlines | corechart |
| Waterfall Charts | corechart |
| Word Trees | wordtree |
