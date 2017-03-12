---
title: Point Percentage of Driver's Champion per Formula 1® Season
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": "#f3a935",
            "borderColor": "#f68639",
            "borderWidth": 1,
            "data": [
                17.86,
                16.15,
                18.75,
                15.97,
                19.48,
                23.81,
                15.54,
                20.83,
                16.22,
                14.35,
                18.22,
                17.0,
                18.67,
                21.95,
                16.0,
                21.6,
                19.0,
                18.55,
                16.11,
                22.91,
                13.89,
                22.55,
                20.33,
                18.93,
                14.67,
                19.85,
                17.25,
                16.94,
                16.0,
                13.6,
                19.14,
                13.33,
                11.03,
                15.99,
                18.77,
                18.25,
                18.0,
                18.34,
                22.5,
                19.0,
                19.5,
                23.82,
                25.96,
                23.8,
                22.12,
                23.08,
                23.32,
                18.33,
                24.04,
                18.27,
                24.43,
                27.83,
                32.58,
                14.9,
                21.08,
                18.02,
                19.09,
                16.59,
                13.96,
                14.76,
                13.34,
                20.43,
                13.91,
                20.69,
                19.01,
                19.85,
                18.15
            ],
            "label": "Point Percentage"
        }
    ],
    "labels": [
        "1950",
        "1951",
        "1952",
        "1953",
        "1954",
        "1955",
        "1956",
        "1957",
        "1958",
        "1959",
        "1960",
        "1961",
        "1962",
        "1963",
        "1964",
        "1965",
        "1966",
        "1967",
        "1968",
        "1969",
        "1970",
        "1971",
        "1972",
        "1973",
        "1974",
        "1975",
        "1976",
        "1977",
        "1978",
        "1979",
        "1980",
        "1981",
        "1982",
        "1983",
        "1984",
        "1985",
        "1986",
        "1987",
        "1988",
        "1989",
        "1990",
        "1991",
        "1992",
        "1993",
        "1994",
        "1995",
        "1996",
        "1997",
        "1998",
        "1999",
        "2000",
        "2001",
        "2002",
        "2003",
        "2004",
        "2005",
        "2006",
        "2007",
        "2008",
        "2009",
        "2010",
        "2011",
        "2012",
        "2013",
        "2014",
        "2015",
        "2016",
        "2017"
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
new Chart("chart", {
    data: data,
    type: 'bar',
    options: options
});
</script>

This chart showcases the dominance of the Driver's Championship winner by displaying the percentage of points earned at the end of the season. Years with a greater percentage indicate a greater dominance. This percentage is calculated as:

$$ \mathbf{100 \cdot \frac{EarnedPoints}{TotalPoints}} $$

#### Data Table

| Year | Point Percentage |
|--|--|
| 1950 | 17.86 |
| 1951 | 16.15 |
| 1952 | 18.75 |
| 1953 | 15.97 |
| 1954 | 19.48 |
| 1955 | 23.81 |
| 1956 | 15.54 |
| 1957 | 20.83 |
| 1958 | 16.22 |
| 1959 | 14.35 |
| 1960 | 18.22 |
| 1961 | 17.0 |
| 1962 | 18.67 |
| 1963 | 21.95 |
| 1964 | 16.0 |
| 1965 | 21.6 |
| 1966 | 19.0 |
| 1967 | 18.55 |
| 1968 | 16.11 |
| 1969 | 22.91 |
| 1970 | 13.89 |
| 1971 | 22.55 |
| 1972 | 20.33 |
| 1973 | 18.93 |
| 1974 | 14.67 |
| 1975 | 19.85 |
| 1976 | 17.25 |
| 1977 | 16.94 |
| 1978 | 16.0 |
| 1979 | 13.6 |
| 1980 | 19.14 |
| 1981 | 13.33 |
| 1982 | 11.03 |
| 1983 | 15.99 |
| 1984 | 18.77 |
| 1985 | 18.25 |
| 1986 | 18.0 |
| 1987 | 18.34 |
| 1988 | 22.5 |
| 1989 | 19.0 |
| 1990 | 19.5 |
| 1991 | 23.82 |
| 1992 | 25.96 |
| 1993 | 23.8 |
| 1994 | 22.12 |
| 1995 | 23.08 |
| 1996 | 23.32 |
| 1997 | 18.33 |
| 1998 | 24.04 |
| 1999 | 18.27 |
| 2000 | 24.43 |
| 2001 | 27.83 |
| 2002 | 32.58 |
| 2003 | 14.9 |
| 2004 | 21.08 |
| 2005 | 18.02 |
| 2006 | 19.09 |
| 2007 | 16.59 |
| 2008 | 13.96 |
| 2009 | 14.76 |
| 2010 | 13.34 |
| 2011 | 20.43 |
| 2012 | 13.91 |
| 2013 | 20.69 |
| 2014 | 19.01 |
| 2015 | 19.85 |
| 2016 | 18.15 |
| 2017 |   |

<small>Download Data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})</small>