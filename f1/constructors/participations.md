---
title: Rank of Formula 1® Constructor Teams by Number of Participations
layout: page
---

<canvas id="chart" width="400" height="180"></canvas>
<script>
var data = {
    "datasets": [
        {
            "backgroundColor": [
                "EB212E",
                "AAAAAA",
                "FFF8F6",
                "274B72",
                "09630C",
                "204FE0",
                "1B1D1D",
                "243F73",
                "F6CF00",
                "0F5DBB",
                "FFA500",
                "144D44",
                "E53524",
                "73C2FB",
                "FFFF01",
                "381ea0",
                "C0BEC3",
                "0C00A3",
                "C35503",
                "3da48e",
                "D70028",
                "273027",
                "888888",
                "888888",
                "B21827",
                "FFFFFF",
                "025839",
                "D33949",
                "888888",
                "FA9B27",
                "888888",
                "095921",
                "888888",
                "0D1773",
                "888888",
                "888888",
                "888888",
                "F6CA46",
                "FFFFFF",
                "888888",
                "20359D",
                "1A2446",
                "888888",
                "888888",
                "025839",
                "888888",
                "457439",
                "BE9D56",
                "124411",
                "5E0A16",
                "273027",
                "888888",
                "FFFFFF",
                "FFFFFF",
                "243F73",
                "AAAAAA",
                "DDDDDD",
                "888888",
                "888888",
                "A3805E",
                "5E0A16",
                "E30010",
                "243F73",
                "888888",
                "006400",
                "F60002",
                "888888",
                "888888",
                "336667",
                "888888",
                "888888",
                "888888",
                "07316F",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "2077C9",
                "888888",
                "888888",
                "EA2040",
                "888888",
                "3FB2B3",
                "888888",
                "C4333B",
                "E2F833",
                "FFA500",
                "888888",
                "888888",
                "888888",
                "343434",
                "888888",
                "888888",
                "FC8881",
                "888888",
                "1A284B",
                "888888",
                "888888",
                "888888",
                "DBC75F",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888",
                "888888"
            ],
            "borderColor": [
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444",
                "444444"
            ],
            "borderWidth": 1,
            "data": [
                2100.0,
                1585.0,
                1339.0,
                881.0,
                871.0,
                706.0,
                672.0,
                662.0,
                629.0,
                611.0,
                590.0,
                562.0,
                524.0,
                520.0,
                500.0,
                450.0,
                436.0,
                412.0,
                342.0,
                314.0,
                280.0,
                268.0,
                260.0,
                252.0,
                244.0,
                236.0,
                231.0,
                226.0,
                216.0,
                211.0,
                194.0,
                170.0,
                165.0,
                165.0,
                162.0,
                155.0,
                154.0,
                154.0,
                152.0,
                144.0,
                140.0,
                134.0,
                133.0,
                131.0,
                128.0,
                123.0,
                121.0,
                114.0,
                112.0,
                109.0,
                103.0,
                102.0,
                98.0,
                97.0,
                93.0,
                87.0,
                84.0,
                82.0,
                81.0,
                79.0,
                78.0,
                78.0,
                77.0,
                76.0,
                76.0,
                76.0,
                71.0,
                71.0,
                71.0,
                66.0,
                64.0,
                59.0,
                58.0,
                55.0,
                54.0,
                54.0,
                52.0,
                48.0,
                47.0,
                46.0,
                43.0,
                42.0,
                42.0,
                41.0,
                40.0,
                40.0,
                39.0,
                34.0,
                34.0,
                32.0,
                32.0,
                29.0,
                28.0,
                26.0,
                25.0,
                22.0,
                21.0,
                21.0,
                19.0,
                19.0,
                18.0,
                17.0,
                17.0,
                16.0,
                15.0,
                15.0,
                14.0,
                14.0,
                14.0,
                13.0,
                13.0,
                11.0,
                11.0,
                11.0,
                11.0,
                11.0,
                10.0,
                9.0,
                9.0,
                8.0
            ],
            "label": "Participations"
        }
    ],
    "labels": [
        "Ferrari",
        "McLaren",
        "Williams",
        "Tyrrell",
        "Team Lotus",
        "Sauber",
        "Minardi",
        "Brabham",
        "Renault",
        "Ligier",
        "Arrows",
        "BRM",
        "March",
        "Benetton",
        "Jordan",
        "Red Bull",
        "Maserati",
        "Toro Rosso",
        "Force India",
        "Mercedes",
        "Toyota",
        "Cooper-Climax",
        "Surtees",
        "Osella",
        "Alfa Romeo",
        "BAR",
        "Lotus-Climax",
        "Kurtis Kraft",
        "Larrousse",
        "Shadow",
        "Footwork",
        "Jaguar",
        "Lola",
        "Prost",
        "ATS",
        "Fittipaldi",
        "Ensign",
        "Lotus F1",
        "Honda",
        "Dallara",
        "BMW Sauber",
        "Cooper-Maserati",
        "Zakspeed",
        "Toleman",
        "Lotus-Ford",
        "AGS",
        "Lotus-BRM",
        "HRT",
        "Caterham",
        "Marussia",
        "Cooper",
        "Gordini",
        "Stewart",
        "Hesketh",
        "Brabham-Climax",
        "McLaren-Ford",
        "Porsche",
        "Talbot-Lago",
        "Coloni",
        "Wolf",
        "Manor Marussia",
        "Super Aguri",
        "Brabham-Repco",
        "Euro Brun",
        "Lotus",
        "Virgin",
        "Matra",
        "RAM",
        "Vanwall",
        "Pacific",
        "Leyton House",
        "Brabham-Alfa Romeo",
        "Brabham-Ford",
        "Iso Marlboro",
        "Connaught",
        "Forti",
        "Onyx",
        "Rial",
        "HWM",
        "Penske",
        "March-Ford",
        "Fondmetal",
        "Haas F1 Team",
        "Brabham-BRM",
        "Matra-Ford",
        "Simtek",
        "Kuzma",
        "Brawn",
        "Spyker",
        "Lambo",
        "Merzario",
        "Simca",
        "MF1",
        "Shadow-Ford",
        "Spirit",
        "Watson",
        "Cooper-BRM",
        "Eagle-Weslake",
        "BRP",
        "Embassy Hill",
        "Veritas",
        "Epperly",
        "Scirocco",
        "Parnelli",
        "Andrea Moda",
        "Lesovsky",
        "De Tomaso",
        "Life",
        "McLaren-BRM",
        "Eagle-Climax",
        "ERA",
        "Aston Martin",
        "Emeryson",
        "Lancia",
        "McLaren-Alfa Romeo",
        "Tecno",
        "Stevens",
        "March-Alfa Romeo",
        "Scarab",
        "Boro"
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

| # | Constructor | Participations |
|--|--|--|
| 1. | Ferrari 🇮🇹 | 2100 |
| 2. | McLaren 🇬🇧 | 1585 |
| 3. | Williams 🇬🇧 | 1339 |
| 4. | Tyrrell 🇬🇧 | 881 |
| 5. | Team Lotus 🇬🇧 | 871 |
| 6. | Sauber 🇨🇭 | 706 |
| 7. | Minardi 🇮🇹 | 672 |
| 8. | Brabham 🇬🇧 | 662 |
| 9. | Renault 🇫🇷 | 629 |
| 10. | Ligier 🇫🇷 | 611 |
| 11. | Arrows 🇬🇧 | 590 |
| 12. | BRM 🇬🇧 | 562 |
| 13. | March 🇬🇧 | 524 |
| 14. | Benetton 🇮🇹 | 520 |
| 15. | Jordan 🇮🇪 | 500 |
| 16. | Red Bull 🇦🇹 | 450 |
| 17. | Maserati 🇮🇹 | 436 |
| 18. | Toro Rosso 🇮🇹 | 412 |
| 19. | Force India 🇮🇳 | 342 |
| 20. | Mercedes 🇩🇪 | 314 |
| 21. | Toyota 🇯🇵 | 280 |
| 22. | Cooper-Climax 🇬🇧 | 268 |
| 23. | Surtees 🇬🇧 | 260 |
| 24. | Osella 🇮🇹 | 252 |
| 25. | Alfa Romeo 🇮🇹 | 244 |
| 26. | BAR 🇬🇧 | 236 |
| 27. | Lotus-Climax 🇬🇧 | 231 |
| 28. | Kurtis Kraft 🇺🇸 | 226 |
| 29. | Larrousse 🇫🇷 | 216 |
| 30. | Shadow 🇬🇧 | 211 |
| 31. | Footwork 🇬🇧 | 194 |
| 32. | Jaguar 🇬🇧 | 170 |
| 33. | Lola 🇬🇧 | 165 |
| 34. | Prost 🇫🇷 | 165 |
| 35. | ATS 🇮🇹 | 162 |
| 36. | Fittipaldi 🇧🇷 | 155 |
| 37. | Ensign 🇬🇧 | 154 |
| 38. | Lotus F1 🇬🇧 | 154 |
| 39. | Honda 🇯🇵 | 152 |
| 40. | Dallara 🇮🇹 | 144 |
| 41. | BMW Sauber 🇩🇪 | 140 |
| 42. | Cooper-Maserati 🇬🇧 | 134 |
| 43. | Zakspeed 🇩🇪 | 133 |
| 44. | Toleman 🇬🇧 | 131 |
| 45. | Lotus-Ford 🇬🇧 | 128 |
| 46. | AGS 🇫🇷 | 123 |
| 47. | Lotus-BRM 🇬🇧 | 121 |
| 48. | HRT 🇪🇸 | 114 |
| 49. | Caterham 🇲🇾 | 112 |
| 50. | Marussia 🇷🇺 | 109 |
| 51. | Cooper 🇬🇧 | 103 |
| 52. | Gordini 🇫🇷 | 102 |
| 53. | Stewart 🇬🇧 | 98 |
| 54. | Hesketh 🇬🇧 | 97 |
| 55. | Brabham-Climax 🇬🇧 | 93 |
| 56. | McLaren-Ford 🇬🇧 | 87 |
| 57. | Porsche 🇩🇪 | 84 |
| 58. | Talbot-Lago 🇫🇷 | 82 |
| 59. | Coloni 🇮🇹 | 81 |
| 60. | Wolf 🇨🇦 | 79 |
| 61. | Manor Marussia 🇬🇧 | 78 |
| 62. | Super Aguri 🇯🇵 | 78 |
| 63. | Brabham-Repco 🇬🇧 | 77 |
| 64. | Euro Brun 🇮🇹 | 76 |
| 65. | Lotus 🇲🇾 | 76 |
| 66. | Virgin 🇬🇧 | 76 |
| 67. | Matra 🇫🇷 | 71 |
| 68. | RAM 🇬🇧 | 71 |
| 69. | Vanwall 🇬🇧 | 71 |
| 70. | Pacific 🇬🇧 | 66 |
| 71. | Leyton House 🇬🇧 | 64 |
| 72. | Brabham-Alfa Romeo 🇬🇧 | 59 |
| 73. | Brabham-Ford 🇬🇧 | 58 |
| 74. | Iso Marlboro 🇬🇧 | 55 |
| 75. | Connaught 🇬🇧 | 54 |
| 76. | Forti 🇮🇹 | 54 |
| 77. | Onyx 🇬🇧 | 52 |
| 78. | Rial 🇩🇪 | 48 |
| 79. | HWM 🇬🇧 | 47 |
| 80. | Penske 🇺🇸 | 46 |
| 81. | March-Ford 🇬🇧 | 43 |
| 82. | Fondmetal 🇮🇹 | 42 |
| 83. | Haas F1 Team 🇺🇸 | 42 |
| 84. | Brabham-BRM 🇬🇧 | 41 |
| 85. | Matra-Ford 🇫🇷 | 40 |
| 86. | Simtek 🇬🇧 | 40 |
| 87. | Kuzma 🇺🇸 | 39 |
| 88. | Brawn 🇬🇧 | 34 |
| 89. | Spyker 🇳🇱 | 34 |
| 90. | Lambo 🇮🇹 | 32 |
| 91. | Merzario 🇮🇹 | 32 |
| 92. | Simca 🇫🇷 | 29 |
| 93. | MF1 🇷🇺 | 28 |
| 94. | Shadow-Ford 🇬🇧 | 26 |
| 95. | Spirit 🇬🇧 | 25 |
| 96. | Watson 🇺🇸 | 22 |
| 97. | Cooper-BRM 🇬🇧 | 21 |
| 98. | Eagle-Weslake 🇺🇸 | 21 |
| 99. | BRP 🇬🇧 | 19 |
| 100. | Embassy Hill 🇬🇧 | 19 |
| 101. | Veritas 🇩🇪 | 18 |
| 102. | Epperly 🇺🇸 | 17 |
| 103. | Scirocco 🇬🇧 | 17 |
| 104. | Parnelli 🇺🇸 | 16 |
| 105. | Andrea Moda 🇮🇹 | 15 |
| 106. | Lesovsky 🇺🇸 | 15 |
| 107. | De Tomaso 🇮🇹 | 14 |
| 108. | Life 🇮🇹 | 14 |
| 109. | McLaren-BRM 🇬🇧 | 14 |
| 110. | Eagle-Climax 🇺🇸 | 13 |
| 111. | ERA 🇬🇧 | 13 |
| 112. | Aston Martin 🇬🇧 | 11 |
| 113. | Emeryson 🇬🇧 | 11 |
| 114. | Lancia 🇮🇹 | 11 |
| 115. | McLaren-Alfa Romeo 🇬🇧 | 11 |
| 116. | Tecno 🇮🇹 | 11 |
| 117. | Stevens 🇺🇸 | 10 |
| 118. | March-Alfa Romeo 🇬🇧 | 9 |
| 119. | Scarab 🇺🇸 | 9 |
| 120. | Boro 🇳🇱 | 8 |

#### Statistic Summary

| **Row Count** | 120.000 |
| **Total Sum** | 23059.000 |
| **Mean (Average)** | 192.158 |
| **Maximum** | 2100.000 |
| **75th Percentile** | 211.000 |
| **Median** | 79.000 |
| **25th Percentile** | 32.000 |
| **Minimum** | 8.000 |
| **Variance** | 95126.467 |
| **Standard Deviation** | 308.426 |

Download data: [json]({{ page.url | replace:'.html','.json' }}), [csv]({{ page.url | replace:'.html','.csv' }})