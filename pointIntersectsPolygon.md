# Point Intersects Polygon


### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex |  Magellan Indexed
--- | --- | --- | --- | --- 
8 | 2.966 | 6.00233 | 1.120666667 |   31.706
16 |  3.114666667 | 8.96567 | 3.878333333 |   27.765
24 |  2.715333333 | 7.30667 | 3.802666667 |   30.854
          
### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex
--- | --- | --- | --- 
8 | 2.841 | 2.231 | 2.116666667 
16 | 3.199333333 |  2.13033 | 1.625 
24 |  3.163666667 | 2.39267 | 1.870666667 
          
### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex
--- | --- | --- | --- 
8 | 4.565666667 | 2.17033 | 3.794666667 
16 | 3.994333333 |  2.29233 | 3.029333333
24 | 3.870666667 |  2.07867 | 3.083333333
          
### Table IV Comparing systems without indexers, no partitions
Cores |  Spatial-Spark Partitioned Spatial Join | STARK w/o Indexer |  Magellan w/o Indexer
 --- | --- | --- | --- 
8 |15.0203 |  6.54 |    31.662
16  | 14.3707 | 7.091 |   33.652
24 | 13.3583 |  6.883666667 |   26.611
          
### Table V Comparing systems without indexers, 8 partitions
Cores |  Spatial-Spark Partitioned Spatial Join  | STARK w/o Indexer
 --- | --- | --- 
8  | 8.358 |  2.985 
16 | 7.176 |  1.996 
24 | 7.521 |  2.432666667 
           
### Table VI Comparing systems without indexers, 16 partitions     
Cores |  Spatial-Spark Partitioned Spatial Join  | STARK w/o Indexer
 --- | --- | --- 
8 |  5.207 |  3.99 
16 | 4.683 |  3.591333333 
24 | 4.16533 |  3.290333333 
