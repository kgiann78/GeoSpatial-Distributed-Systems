# Polygon Contains Polygon


### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex | GeoSpark Indexed
--- | --- | --- | --- | --- 
8 | 5.866333333 |  9.21467 |  5.167 |  5.28467
16 |  6.15 |   8.54933 |  6.407 |  4.97733
24 |  6.185333333 |  11.186 |   5.946 |  4.909
          
### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex | GeoSpark Indexed
--- | --- | --- | --- | ---
8 | 4.167666667 |  2.97467 |  3.289 |  4.177666667
16 |  4.169 |  2.724 |  2.566 |  4.271
24 |  3.684666667 |  2.99033 |  2.522 |  4.048
          
### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex | GeoSpark Indexed
--- | --- | --- | --- | ---
8 | 5.445666667 |  2.796 |  4.853 |  3.24067
16 |  4.943 |  2.694 |  3.975 |  3.521333333
24 |  4.946333333 |  2.708 |  3.574 |  3.699
          
### Table IV Comparing systems without indexers, no partitions
Cores |  Spatial-Spark Partitioned Spatial Join  | STARK w/o Indexer | GeoSpark w/o Indexer
--- | --- | --- | ---
8 | 26.1217 |  5.837 |  16.997 
16 | 28.2593 |  6.904 |  16.689 
24 | 28.4877 |  7.116 |  16.71233333 
          
### Table V Comparing systems without indexers, 8 partitions
Cores |  Spatial-Spark Partitioned Spatial Join  | STARK w/o Indexer | GeoSpark w/o Indexer
--- | --- | --- | --- 
8 | 13.247 |   3.61 |   4.890666667 
16 | 11.2867 |  2.431 |  5.046333333 
24 | 11.4163 |  2.573 |  4.318333333 
          
### Table VI Comparing systems without indexers, 16 partitions     
Cores |  Spatial-Spark Partitioned Spatial Join  | STARK w/o Indexer | GeoSpark w/o Indexer
--- | --- | --- | --- 
8 | 8.014 |  4.798 |  10.332 
16 | 7.53833 |  4.256 |  3.363333333  
24 | 7.60033 |  3.671 |  3.699666667 
