---
title: Rank of Formula 1® Drivers by Number of Starts from P1 at Marina Bay Street Circuit
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
                3.0,
                3.0,
                1.0,
                1.0,
                1.0
            ],
            "label": "Number Of Starts From P1"
        }
    ],
    "labels": [
        "Lewis Hamilton",
        "Sebastian Vettel",
        "Felipe Massa",
        "Fernando Alonso",
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

| # | Driver | Number Of Starts From P1 |
|--|--|--|
| 1. | Lewis Hamilton 🇬🇧 | 3 |
| 2. | Sebastian Vettel 🇩🇪 | 3 |
| 3. | Felipe Massa 🇧🇷 | 1 |
| 4. | Fernando Alonso 🇪🇸 | 1 |
| 5. | Nico Rosberg 🇩🇪 | 1 |

#### Statistic Summary

| **Row Count** | 5.000 |
| **Total Sum** | 9.000 |
| **Mean (Average)** | 1.800 |
| **Maximum** | 3.000 |
| **75th Percentile** | 3.000 |
| **Median** | 1.000 |
| **25th Percentile** | 1.000 |
| **Minimum** | 1.000 |
| **Variance** | 0.960 |
| **Standard Deviation** | 0.980 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})