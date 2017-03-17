---
title: Rank of Formula 1® Drivers by Number of Laps Led at Baku City Circuit
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "#f3a935"
            ],
            "borderColor": [
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                51.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Nico Rosberg"
    ]
};
var options = {
  legend: {
    display: false
  },
  scales: {
    xAxes: [{
      ticks: {
        beginAtZero: true,
        maxRotation: 180,
        display: window.innerWidth > 800
      }
    }],
    yAxes: [{
      ticks: {
        beginAtZero: true
      }
    }]
  },
  onResize: function(chart, size) {
    chart.options.scales.xAxes[0].ticks.display = size.width > 800;
  }
};
var chart = new Chart("chart", {
    data: data,
    type: 'bar',
    options: options
});
</script>



### Data Table

| # | Driver | Number Of Laps Led |
|--|--|--|
| 1. | Nico Rosberg 🇩🇪 | 51 |

#### Statistic Summary

| **Row Count** | 1.000 |
| **Total Sum** | 51.000 |
| **Mean (Average)** | 51.000 |
| **Maximum** | 51.000 |
| **75th Percentile** | 51.000 |
| **Median** | 51.000 |
| **25th Percentile** | 51.000 |
| **Minimum** | 51.000 |
| **Variance** | 0.000 |
| **Standard Deviation** | 0.000 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})