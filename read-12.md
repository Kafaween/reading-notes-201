# Charts

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

## Chart.js comes with the following built-in chart types:

> Scatter

> Radar

> Polar Area

> Bubble

> line

> pie

> bar

![](https://canvasjs.com/wp-content/uploads/images/gallery/javascript-charts/overview/javascript-charts-graphs-index-data-label.png)


![](https://miro.medium.com/max/629/1*rzNBRBt1RCr4NsN4Lb7V1Q.png)

This concept was introduced in Chart.js  to keep configuration DRY , and allow for changing options globally across chart types, avoiding the need to specify options for each instance, or the default for a particular chart type.

Chart.js merges the options object passed to the chart with the global configuration using chart type defaults and scales defaults appropriately. This way you can be as specific as you would like in your individual chart configuration, while still changing the defaults for all chart types where applicable. The global general options are defined in Chart.defaults. The defaults for each chart type are discussed in the documentation for that chart type.

The following example would set the interaction mode to 'nearest' for all charts where this was not overridden by the chart type defaults or the options passed to the constructor on creation.
