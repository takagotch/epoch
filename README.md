### epoch
---
https://github.com/epochjs/epoch

http://epochjs.github.io/epoch/basic/
```
<script src="js/d3.min.js"></script>
<script src="js/epoch.min.js"></script>

<link rel="stylesheet" type="text/css" href="css/epoch.min.css">

<div id="area" class="epoch category10" style="height: 200px;"></div>
<script>
  $('#areaChart').epoch({
    type: 'area',
    data: areaChartData
  });
</script>

<div id="barChart" style="width: 300px; height: 100px"></div>
<script>
  $('#barChart').epoch({
    type: 'bar',
    data: barChartData
  });
</script>

<div id="lineChart" style="width: 700px; height: 250px"></div>
<script>
  $('#lineChart').epoch({
    type: 'line',
    data: lineChartData
  });
</script>

<div id="pie" style="width: 400px; height: 400px"></div>
<script>
  $('#pie').epoch({
    type: 'pie',
    data: pieData
  });
</script>

<div id="scatter" style="width: 500px; height: 500px"></div>
<script>
  $('#scatter').epoch({
    type: 'scatter',
    data: scatterData
  });
</script>
```

```js
var data = [
  { label: 'Layer 1', values: [ {x: 0, y: 0}, {x: 1, y: 1}, {x: 2, y: 2} ] },
  { label: 'Layer 2', values: [ {x: 0, y: 0}, {x: 1, y: 1}, {x: 2, y: 4} ] }
];

var areaChartInstance = $('#area').epoch({
 type: 'area',
 data: data,
 axes: ['left', 'right', 'bottom']
});

var areaChartData = [
  {
    label: "Layer 1",
    values: [ {x: 0, y: 100}, {x: 20, y: 1000}, ... ]
  },
  {
    label: "Layer 2",
    values: [ {x: 0, y: 78}, {x: 20, y: 98}, ... ]
  },
];

var barChartData = [
  {
    label: '',
    values: [
      { x: 'A', y: 30 },
      { x: 'B', y: 10 },
      { x: 'C', y: 12 }
    ]
  },
    label: 'Series 2',
    values: [
  { x: 'A', y: 20 },
  { x: 'B', y: 39 },
  { x: 'C', y: 8 }
  ]
];

var lineChartData = [
  {
    label: "Series 1",
    values: [ { x: 0, y: 100}, {x:20, y: 1000}, ... ]
  },
  {
    label: "Series 2",
    values: [ {x: 20, y: 78},{x: 30, y: 98}, ... ]
  },
]

var pieData = [
  { label: 'Slice 1', value: 10 },
  { label: 'Slice 2', value: 20 },
  { label: 'Slice 3', value: 40 },
  { label: 'Slice 4', value: 30 }
]

var scatterData = [
  {
    label: "Group 1",
    values: [ {x: 5, y: 100}, {x: 93, y: 1424}, ...]
  },
  {
    label: "Group 2",
    values: [ {x: -52, y: 78}, {x: 120, y: 17}, ...]
  }
];

var bubleData = [
  {
    label: 'Group 1',
    values: [
      {x: 10, y: 40, r: 2},
      {x: 48, y: 17, r: 5},
      {x: 9, y: 33, r: 10}
    ]
  }
];
```

```
```


