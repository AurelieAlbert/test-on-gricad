# Tests on gricad

In this repo I will put the notebooks I ran on gricad servers (dahu for the moment).

## First test of scalability - April 2020

Computation of temporal and spatial means over 3 month of hourly surface data in Acores region extracted from eNATL60-BLBT02 run. The notebooks are : 

Results for chunks :

 
|---|---|---|---|
| Number of workers   |  5  |  10  |  20  |
|---|---|---|---|
|  Spatial mean over 2108 time steps | 16min 26s  |  7min 7s  | 4min 58s  |
|---|---|---|---|
| Temporal mean over 700x1200 grid points  |  14min 16s  | 5min 41s  | 3min 52s  |
|---|---|---|---|
