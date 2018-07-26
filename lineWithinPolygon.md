# Line Within Polygon

### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join | Magellan Indexed
--- | --- | --- | ---
8 | 18.52633333 |  | 7.309
16 | 19.06266667 |  | 8.958
24 | 18.192 |  | 7.885

### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join (64 Partitions)
--- | --- | --- 
8 | 6.662333333 | 25.5593
16 | 7.655666667 | 17.6893
24 | 6.652666667 | 18.734

### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex | Spatial Spark Broadcast Spatial Join  (256 Partitions)
--- | --- | --- 
8 | 8.343333333 | 29.6363
16 | 8.143 | 21.223
24 | 7.581666667 | 21.156

### Table IV Comparing systems without indexers, no partitions
Cores | Spatial-Spark Partitioned Spatial Join | Magellan
--- | --- | ---
8 | | 18.748
16  | | 19.655
24  | | 18.221

### Table V Comparing systems without indexers, 256 Partitions
Cores |  Spatial-Spark Partitioned Spatial Join 
--- | --- 
8  | 172.867
16 | 135.273
24 | 149.172

### Table VI Comparing systems without indexers, 512 Partitions
Cores | Spatial-Spark Partitioned Spatial Join 
--- | --- 
8 | 187.909
16 | 134.413
24 | 122.559
