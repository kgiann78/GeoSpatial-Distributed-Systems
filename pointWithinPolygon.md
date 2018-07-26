# Point Within Polygon


### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  |  Magellan Indexed
--- | --- | ---  | --- 
8 | 3.005333333| 5.789  |   8.31
16 |  2.924 |6.43  |    8.222
24 |  2.963 |6.61433   |  8.796
          
### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join 
--- | --- | ---
8 | 3.129666667| 2.096
16 |  2.873 |2.119
24 |  3.194666667| 2.174 
          
### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join 
--- | --- | --- 
8 | 4.909333333| 2.25
16 |  4.232333333 |2.03067
24 |  3.884666667 |2.082
          
### Table IV Comparing systems without indexers, no partitions
Cores |  Spatial-Spark Partitioned Spatial Join |  Magellan w/o Indexer
 --- | --- | --- 
8 |  12.314   |   19.141
16 |    15.449  |    20.783
24 |    15.5243  |   17.362
          
### Table V Comparing systems without indexers, 8 partitions
Cores |  Spatial-Spark Partitioned Spatial Join 
 --- | --- 
8 |   7.08133
16 |    7.38333
24 |    7.486
           
### Table VI Comparing systems without indexers, 16 partitions     
Cores |  Spatial-Spark Partitioned Spatial Join 
 --- | --- 
8 |   5.31833
16 |    6.01167
24 |    4.48633
