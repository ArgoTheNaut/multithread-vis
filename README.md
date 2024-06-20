# multithread-vis

Visualization for multiple parallel series over time.

This repository plots a data collection such as the example below:
|name | series | start | end|
|-|-|-|-|
| book 1 | A | 2019-08-01 | 2020-09-03|
| book 2 | A | 2021-05-15 | 2021-11-12|
| book 3 | A | 2022-09-01 | 2023-12-25|
| book A | B | 2020-06-06 | 2021-03-02|
| book B | B | 2022-02-27 | 2022-12-12|
| ORR | - | 2019-08-07 | 2020-03-14|
| TGOA | - | 2020-10-20 | 2021-07-03|
| KoA | - | 2021-11-01 | 2021-12-05|
| TMToT | - | 2022-01-15 | 2022-06-09|
| S&TMFoA | - | 2020-02-12 | 2021-03-04|
| Cider Recipes | - | 2021-09-12 | 2023-01-04|
| MCS | - | 2024-05-01 | 2024-06-13|
| Overflow | - | 2021-09-01 | 2022-08-12|

and converts the data into a visual:  
![Several parallel time series are used to represent the data input to the program](image.png)