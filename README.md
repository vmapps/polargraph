# polargraph
Transform data from Polar A360 tracker into HTML dynamic graphs

## Purpose 
Purpose of this very simple tool is to :
- read JSON data from Polar A360 tracker 
- add data to web graph generated with Ploty javascript module
- let user add/remove new data to the existing graph
This small project has been first been developed to complete web
interfaces proposed by Polar.

## Requirements
Following javascript modules are required :
- [jQuery](https://jquery.com/)
- [jQuery UI](https://jqueryui.com/)
- [Plotly.js](https://plot.ly/javascript/)

## Run web server
You could run a simple web server by running that commad into root directory:
```
$ python -m SimpleHTTPServer 80
```

