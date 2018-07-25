# Polygon Overlaps Polygon

### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join
--- | --- | --- 
8 | 6.415666667 | 8.68733
16 | 6.572666667 | 9.307
24 | 6.665666667 | 5.79767

### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join 
--- | --- | --- 
8 | 4.018666667 | 2.95967
16 | 4.162333333 | 2.785
24 | 3.903333333 | 3.03667

### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join 
--- | --- | --- 
8 | 5.244666667 |  2.92733
16 | 4.356666667 | 3.08467
24 | 4.801333333 | 3.069

### Table IV Comparing systems without indexers, no partitions
Cores | Exareme |  Spatial-Spark Partitioned Spatial Join 
--- | --- | --- 
8 | No experiments without indexer | 27.3463
16 |  |25.8323
24 |  |26.782

### Table V Comparing systems without indexers, 8 partitions
Cores | Exareme |  Spatial-Spark Partitioned Spatial Join
--- | --- | --- 
8 | No experiments without indexer | 12.361
16 | | 12.372
24 | | 11.989

### Table VI Comparing systems without indexers, 16 partitions     
Cores | Exareme |  Spatial-Spark Partitioned Spatial Join 
--- | --- | --- 
8 | No experiments without indexer | 8.30867
16 | | 8.25933
24 | | 7.34933
