# Point Intersects Line


### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex   | STARK LiveIndex 
--- | --- | --- 
8 | 5.230333333 |  58.169
16 |  5.324666667 |  78.7197
24 |  5.582 |  84.255
          
### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex  | STARK LiveIndex
--- | --- | --- 
8 | 3.76  |  146.7806667
16 |3.674333333  | 160.84
24 |  3.544666667 |  178.4423333
          
### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex  | STARK LiveIndex
--- | --- | --- 
8 | 5.134 |  130.847
16 | 4.623   | 101.258
24 | 4.660333333 |   106.007
          
### Table IV Comparing systems without indexers, no partitions
Cores |  Spatial-Spark Partitioned Spatial Join | STARK w/o Indexer 
 --- | --- | --- 
8 | | 1568.74
16  |  | 1082.6
24 | | 1320.85
          
### Table V Comparing systems without indexers, 8 partitions
Cores |  Spatial-Spark Partitioned Spatial Join (64 Partitions)  | STARK w/o Indexer
 --- | --- | --- 
8  | 201.138 | 287.395
16 | 226.744 | 201.949
24 | | 197.938
           
### Table VI Comparing systems without indexers, 16 partitions     
Cores |  Spatial-Spark Partitioned Spatial Join (256 Partitions)  | STARK w/o Indexer
 --- | --- | --- 
8 |  178.307 | 251.779
16 | 124.014 | 168.79
24 |143.49 |152.729
