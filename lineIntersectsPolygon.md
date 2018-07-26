# Line Intersects Polygon

### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex | Spatial Spark Broadcast Spatial Join | STARK LiveIndex 
--- | --- | --- | ---
8 | 11.18166667 | 25.992 | 63.44
16 | 10.932 | 17.676 | 85.7193
24 | 9.779333333 | 17.8473 | 79.882

### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex | Spatial Spark Broadcast Spatial Join (256 partitions)| STARK LiveIndex 
--- | --- | --- | ---
8 | 6.643666667 | 31.1643 | 172.071
16 | 6.570666667 | 21.3833 | 183.619
24 | 6.114666667 | 20.2287 | 196.867

### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex | Spatial Spark Broadcast Spatial Join (512 partitions)| STARK LiveIndex 
--- | --- | --- | ---
8 | 7.152333333 | 34.5913 | 132.378
16 | 7.015333333 | 23.5087 | 108.217
24 | 7.722333333 | 23.1947 | 129.245

### Table IV Comparing systems without indexers, no partitions
Cores | Spatial Spark Broadcast Spatial Join (64 partitions)| STARK 
--- | --- | ---
8 | | 672.017
16 | | 647.499
24 | | 509.661

### Table V Comparing systems without indexers, 8 partitions
Cores | Spatial Spark Broadcast Spatial Join (256 partitions)| STARK 
--- | --- | ---
8  | 176.241 | 269.777
16 | 165.314 | 209.012
24 | 173.717 | 158.358

### Table VI Comparing systems without indexers, 16 partitions     
Cores | Spatial Spark Broadcast Spatial Join (512 partitions)| STARK 
--- | --- | ---
8 | 190.424 | 285.78
16 | 138.988 | 210.202
24 | 127.113 | 191.217
