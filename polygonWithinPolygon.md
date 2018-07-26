# Polygon Within Polygon

### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join
--- | --- | --- 
8 | 6.024333333 | 9.16567
16 | 5.830666667 | 8.032
24 | 6.105333333 | 9.29533

### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join 
--- | --- | --- 
8 | 3.778 | 2.80133
16 | 4.215333333 | 2.80567
24 | 3.747 | 3.008

### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join 
--- | --- | --- 
8 | 5.364333333 | 2.937
16 | 4.372 | 2.64567
24 | 4.266333333 | 2.80067

### Table IV Comparing systems without indexers, no partitions
Cores | Spatial-Spark Partitioned Spatial Join 
--- | --- 
8 | 24.1467
16  |26.4613
24  |27.8107

### Table V Comparing systems without indexers, 8 partitions
Cores |  Spatial-Spark Partitioned Spatial Join
--- | --- 
8  | 12.312
16 | 11.939
24 | 11.2147

### Table VI Comparing systems without indexers, 16 partitions     
Cores | Spatial-Spark Partitioned Spatial Join 
--- | --- 
8 | 8.354
16 | 7.44767
24 | 6.48867
