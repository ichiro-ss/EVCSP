# EVCSP
This repository contains the instances used for electric vehicle charging scheduling problem presented at paper "Evaluation of metaheuristic algorithms for the electric vehicle charging scheduling problem.".

This research was done by:

| Name                | Email                     |
|:--------------------|:-------------------------:|
| Seiichiro Sawamura  | ___@___.__                |


## Instances Description
An instance represents charging demands and it was generated as described [below](#instances-generation). All instances files are `.txt` files. Each name and following datas represents:
- We have 'the instance name' at the begining.
- The value under 'vehicles' shows the number of vehicles. Similarly, the number of charging stations(CS) as 'stations' and charging outlets(CO) as 'outlets'.
- Matrix forrowing `distances` gives the distance between each EV and CS. Array is the vehicle and row is the CS.
- Column `max_distances` shows the maximum travel distances for each EVs.
- Matrix `arrive_time` displays the arrival time. Array is the vehicle and row is the CS.
- Matrix `charge_time` indicates the actual charging time. Array is the vehicle and row is the CS.
- Column `already_que_time` gives finish time of already queing EVs for each CO.


## Instanes

| File                  |Number of vehicles|Number of CSs|Number of COs|Distances|Velocities|Charging rates|
|:----------------------|:-----------------|:------------|:------------|:--------|:---------|:------------:|
|n100ld1_20v2_3e_e25_30c|               100|           20|            2|     1-20|      2-3e|    0.25-0.30c|
|n100ld1_20v2_3e_e50_55c|               100|           20|            2|     1-20|      2-3e|    0.50-0.55c|
|n100ld1_20v5_6e_e25_30c|               100|           20|            2|     1-20|      5-6e|    0.25-0.30c|
|n100ld1_20v5_6e_e50_55c|               100|           20|            2|     1-20|      5-6e|    0.50-0.55c|
|n100ld8_40v2_3e_e25_30c|               100|           20|            2|     8-40|      2-3e|    0.25-0.30c|
|n100ld8_40v2_3e_e50_55c|               100|           20|            2|     8-40|      2-3e|    0.50-0.55c|
|n100ld8_40v5_6e_e25_30c|               100|           20|            2|     8-40|      5-6e|    0.25-0.30c|
|n100ld8_40v5_6e_e50_55c|               100|           20|            2|     8-40|      5-6e|    0.50-0.55c|
|n100md1_20v2_3e_e25_30c|               100|           30|            3|     1-20|      2-3e|    0.25-0.30c|
|n100md1_20v2_3e_e50_55c|               100|           30|            3|     1-20|      2-3e|    0.50-0.55c|
|n100md1_20v5_6e_e25_30c|               100|           30|            3|     1-20|      5-6e|    0.25-0.30c|
|n100md1_20v5_6e_e50_55c|               100|           30|            3|     1-20|      5-6e|    0.50-0.55c|
|n100md8_40v2_3e_e25_30c|               100|           30|            3|     8-40|      2-3e|    0.25-0.30c|
|n100md8_40v2_3e_e50_55c|               100|           30|            3|     8-40|      2-3e|    0.50-0.55c|
|n100md8_40v5_6e_e25_30c|               100|           30|            3|     8-40|      5-6e|    0.25-0.30c|
|n100md8_40v5_6e_e50_55c|               100|           30|            3|     8-40|      5-6e|    0.50-0.55c|
|n200ld1_20v2_3e_e25_30c|               200|           20|            2|     1-20|      2-3e|    0.25-0.30c|
|n200ld1_20v2_3e_e50_55c|               200|           20|            2|     1-20|      2-3e|    0.50-0.55c|
|n200ld1_20v5_6e_e25_30c|               200|           20|            2|     1-20|      5-6e|    0.25-0.30c|
|n200ld1_20v5_6e_e50_55c|               200|           20|            2|     1-20|      5-6e|    0.50-0.55c|
|n200ld8_40v2_3e_e25_30c|               200|           20|            2|     8-40|      2-3e|    0.25-0.30c|
|n200ld8_40v2_3e_e50_55c|               200|           20|            2|     8-40|      2-3e|    0.50-0.55c|
|n200ld8_40v5_6e_e25_30c|               200|           20|            2|     8-40|      5-6e|    0.25-0.30c|
|n200ld8_40v5_6e_e50_55c|               200|           20|            2|     8-40|      5-6e|    0.50-0.55c|
|n200md1_20v2_3e_e25_30c|               200|           30|            3|     1-20|      2-3e|    0.25-0.30c|
|n200md1_20v2_3e_e50_55c|               200|           30|            3|     1-20|      2-3e|    0.50-0.55c|
|n200md1_20v5_6e_e25_30c|               200|           30|            3|     1-20|      5-6e|    0.25-0.30c|
|n200md1_20v5_6e_e50_55c|               200|           30|            3|     1-20|      5-6e|    0.50-0.55c|
|n200md8_40v2_3e_e25_30c|               200|           30|            3|     8-40|      2-3e|    0.25-0.30c|
|n200md8_40v2_3e_e50_55c|               200|           30|            3|     8-40|      2-3e|    0.50-0.55c|
|n200md8_40v5_6e_e25_30c|               200|           30|            3|     8-40|      5-6e|    0.25-0.30c|
|n200md8_40v5_6e_e50_55c|               200|           30|            3|     8-40|      5-6e|    0.50-0.55c|
|n300ld1_20v2_3e_e25_30c|               300|           20|            2|     1-20|      2-3e|    0.25-0.30c|
|n300ld1_20v2_3e_e50_55c|               300|           20|            2|     1-20|      2-3e|    0.50-0.55c|
|n300ld1_20v5_6e_e25_30c|               300|           20|            2|     1-20|      5-6e|    0.25-0.30c|
|n300ld1_20v5_6e_e50_55c|               300|           20|            2|     1-20|      5-6e|    0.50-0.55c|
|n300ld8_40v2_3e_e25_30c|               300|           20|            2|     8-40|      2-3e|    0.25-0.30c|
|n300ld8_40v2_3e_e50_55c|               300|           20|            2|     8-40|      2-3e|    0.50-0.55c|
|n300ld8_40v5_6e_e25_30c|               300|           20|            2|     8-40|      5-6e|    0.25-0.30c|
|n300ld8_40v5_6e_e50_55c|               300|           20|            2|     8-40|      5-6e|    0.50-0.55c|
|n300md1_20v2_3e_e25_30c|               300|           30|            3|     1-20|      2-3e|    0.25-0.30c|
|n300md1_20v2_3e_e50_55c|               300|           30|            3|     1-20|      2-3e|    0.50-0.55c|
|n300md1_20v5_6e_e25_30c|               300|           30|            3|     1-20|      5-6e|    0.25-0.30c|
|n300md1_20v5_6e_e50_55c|               300|           30|            3|     1-20|      5-6e|    0.50-0.55c|
|n300md8_40v2_3e_e25_30c|               300|           30|            3|     8-40|      2-3e|    0.25-0.30c|
|n300md8_40v2_3e_e50_55c|               300|           30|            3|     8-40|      2-3e|    0.50-0.55c|
|n300md8_40v5_6e_e25_30c|               300|           30|            3|     8-40|      5-6e|    0.25-0.30c|
|n300md8_40v5_6e_e50_55c|               300|           30|            3|     8-40|      5-6e|    0.50-0.55c|
|n400ld1_20v2_3e_e25_30c|               400|           20|            2|     1-20|      2-3e|    0.25-0.30c|
|n400ld1_20v2_3e_e50_55c|               400|           20|            2|     1-20|      2-3e|    0.50-0.55c|
|n400ld1_20v5_6e_e25_30c|               400|           20|            2|     1-20|      5-6e|    0.25-0.30c|
|n400ld1_20v5_6e_e50_55c|               400|           20|            2|     1-20|      5-6e|    0.50-0.55c|
|n400ld8_40v2_3e_e25_30c|               400|           20|            2|     8-40|      2-3e|    0.25-0.30c|
|n400ld8_40v2_3e_e50_55c|               400|           20|            2|     8-40|      2-3e|    0.50-0.55c|
|n400ld8_40v5_6e_e25_30c|               400|           20|            2|     8-40|      5-6e|    0.25-0.30c|
|n400ld8_40v5_6e_e50_55c|               400|           20|            2|     8-40|      5-6e|    0.50-0.55c|
|n400md1_20v2_3e_e25_30c|               400|           30|            3|     1-20|      2-3e|    0.25-0.30c|
|n400md1_20v2_3e_e50_55c|               400|           30|            3|     1-20|      2-3e|    0.50-0.55c|
|n400md1_20v5_6e_e25_30c|               400|           30|            3|     1-20|      5-6e|    0.25-0.30c|
|n400md1_20v5_6e_e50_55c|               400|           30|            3|     1-20|      5-6e|    0.50-0.55c|
|n400md8_40v2_3e_e25_30c|               400|           30|            3|     8-40|      2-3e|    0.25-0.30c|
|n400md8_40v2_3e_e50_55c|               400|           30|            3|     8-40|      2-3e|    0.50-0.55c|
|n400md8_40v5_6e_e25_30c|               400|           30|            3|     8-40|      5-6e|    0.25-0.30c|
|n400md8_40v5_6e_e50_55c|               400|           30|            3|     8-40|      5-6e|    0.50-0.55c|
