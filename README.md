# TinyMCE Chart Plugin

TinyMCE Chart Plugin with editing charts capabilities. Inserts the chart as an image (with a Base64 src), stores the chart data in the Alt attribute and uses Chart.js for rendering.

![alt screenshot](https://raw.githubusercontent.com/lrusso/TinyMCEChartPlugin/master/chart.png)

## Demo:

https://lrusso.github.io/TinyMCEChartPlugin/demo.htm

## Example of chart code (required to make charts):

```
Chart,15,red
Inside,30,blue
TinyMCE,45,green
```

## How to add it to TinyMCE

Add the Chart plugin script to your TinyMCE Web:
```
<script src="chart.js"></script> 
```

Add the plugin references into your TinyMCE configuration:
```
plugins: "chart",
toolbar1: "chart",
paste_data_images: true,
```
