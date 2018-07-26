# Line Intersects Line

### Table I Comparing systems with indexers, no partitions
Cores | Spatial Spark Broadcast Spatial Join | STARK LiveIndex 
--- | --- | --- 
8 |  | 16.867
16 | | 22.055
24 | | 23.792

### Table II Comparing systems with indexers, 8 partitions       
Cores | Spatial Spark Broadcast Spatial Join (256 partitions)| STARK LiveIndex 
--- | --- | --- 
8 | 1748.71 | 39.791
16 |  | 27.246
24 |  | 28.597

### Table III Comparing systems with indexers, 16 partitions       
Cores | Spatial Spark Broadcast Spatial Join (512 partitions)| STARK LiveIndex 
--- | --- | --- 
8 | 1533.694 | 56.176
16 |  | 41.608
24 |  | 41.942

### Table IV Comparing systems without indexers, no partitions
Cores | STARK 
--- | --- 
8 | 15.646
16 | 14.78
24 | 19.431

### Table V Comparing systems without indexers, 8 partitions
Cores | STARK 
--- | --- 
8  | 3876.38
16 | 4640.05
24 | 4193.12

### Table VI Comparing systems without indexers, 16 partitions     
Cores | STARK 
--- | --- 
8 | 455.907
16 | 492.798
24 | 546.562
