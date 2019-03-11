# TinyMCE Chart Plugin

TinyMCE Chart Plugin. Stores the chart data in the Alt attribute and uses Chart.js for rendering.

![alt screenshot](https://raw.githubusercontent.com/lrusso/TinyMCEChartPlugin/master/Chart.png)

## Demo:

https://lrusso.github.io/TinyMCEChartPlugin/demo.htm

## Example of chart code (required to make charts):

```
Chart,10,red
Inside,30,blue
TinyMCE,50,green
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
