---
title: Rank of Formula 1® Drivers by Number of Fastest Laps at Valencia Street Circuit
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935"
            ],
            "borderColor": [
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                1.0,
                1.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Fastest Laps"
        }
    ],
    "labels": [
        "Felipe Massa",
        "Jenson Button",
        "Nico Rosberg",
        "Sebastian Vettel",
        "Timo Glock"
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

| # | Driver | Number Of Fastest Laps |
|--|--|--|
| 1. | Felipe Massa 🇧🇷 | 1 |
| 2. | Jenson Button 🇬🇧 | 1 |
| 3. | Nico Rosberg 🇩🇪 | 1 |
| 4. | Sebastian Vettel 🇩🇪 | 1 |
| 5. | Timo Glock 🇩🇪 | 1 |

#### Statistic Summary

| **Row Count** | 5.000 |
| **Total Sum** | 5.000 |
| **Mean (Average)** | 1.000 |
| **Maximum** | 1.000 |
| **75th Percentile** | 1.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.000 |
| **Standard Deviation** | 0.000 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})