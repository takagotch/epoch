### epoch
---
https://github.com/epochjs/epoch

```
<script src="js/d3.min.js"></script>
<script src="js/epoch.min.js"></script>

<link rel="stylesheet" type="text/css" href="css/epoch.min.css">

<div id="area" class="epoch category10" style="height: 200px;"></div>
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
    label: "",
    values: [ {}, {}, ... ]
  },
  {
    label: "",
    values: [ {}, {}, ... ]
  },
];

```

```
```


