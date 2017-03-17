---
title: Rank of Formula 1® Drivers by Number of Laps Led at Bahrain International Circuit
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
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
                "#f3a935",
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
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639",
                "#f68639"
            ],
            "borderWidth": 1,
            "data": [
                146.0,
                108.0,
                102.0,
                96.0,
                77.0,
                62.0,
                38.0,
                12.0,
                10.0,
                6.0,
                4.0,
                4.0,
                4.0,
                4.0,
                2.0,
                1.0
            ],
            "label": "Number Of Laps Led"
        }
    ],
    "labels": [
        "Sebastian Vettel",
        "Lewis Hamilton",
        "Felipe Massa",
        "Fernando Alonso",
        "Michael Schumacher",
        "Nico Rosberg",
        "Jenson Button",
        "Kimi Räikkönen",
        "Timo Glock",
        "Rubens Barrichello",
        "Jarno Trulli",
        "Juan Pablo Montoya",
        "Nick Heidfeld",
        "Paul di Resta",
        "Robert Kubica",
        "Romain Grosjean"
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
| 1. | Sebastian Vettel 🇩🇪 | 146 |
| 2. | Lewis Hamilton 🇬🇧 | 108 |
| 3. | Felipe Massa 🇧🇷 | 102 |
| 4. | Fernando Alonso 🇪🇸 | 96 |
| 5. | Michael Schumacher 🇩🇪 | 77 |
| 6. | Nico Rosberg 🇩🇪 | 62 |
| 7. | Jenson Button 🇬🇧 | 38 |
| 8. | Kimi Räikkönen 🇫🇮 | 12 |
| 9. | Timo Glock 🇩🇪 | 10 |
| 10. | Rubens Barrichello 🇧🇷 | 6 |
| 11. | Jarno Trulli 🇮🇹 | 4 |
| 12. | Juan Pablo Montoya 🇨🇴 | 4 |
| 13. | Nick Heidfeld 🇩🇪 | 4 |
| 14. | Paul di Resta 🇬🇧 | 4 |
| 15. | Robert Kubica 🇵🇱 | 2 |
| 16. | Romain Grosjean 🇫🇷 | 1 |

#### Statistic Summary

| **Row Count** | 16.000 |
| **Total Sum** | 676.000 |
| **Mean (Average)** | 42.250 |
| **Maximum** | 146.000 |
| **75th Percentile** | 96.000 |
| **Median** | 12.000 |
| **25th Percentile** | 4.000 |
| **Minimum** | 1.000 |
| **Variance** | 2225.312 |
| **Standard Deviation** | 47.173 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})