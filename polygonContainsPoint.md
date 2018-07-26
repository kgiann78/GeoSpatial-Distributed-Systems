# Polygon Contains Point


### Table I Comparing systems with indexers, no partitions
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex | GeoSpark Indexed |  Magellan Indexed
--- | --- | --- | --- | --- | ---
8 | 3.020333333 | 7.52133 | 0.9113333333 |  3.626666667 | 7.309
16 |  2.799 | 5.073 | 1.055333333 | 3.097 | 8.958
24 |  3.140666667 | 7.56633 | 4.225 | 3.024666667 | 7.885
          
### Table II Comparing systems with indexers, 8 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex | GeoSpark Indexed
--- | --- | --- | --- | ---
8 | 3.358333333 | 1.91133 | 1.706333333 | 1.677333333 
16 |  2.76 |  1.556 | 2.103333333 | 1.379 
24 |  3.155 | 1.62767 | 1.475 | 1.612 
          
### Table III Comparing systems with indexers, 16 partitions       
Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | STARK LiveIndex | GeoSpark Indexed
--- | --- | --- | --- | ---
8 | 4.935666667 | 1.56333 | 3.93  | 1.133 
16 | 4.661666667 | 1.88267 | 3.216 | 1.399333333
24 | 4.161333333 | 1.465 | 2.799666667 | 1.524666667 
          
### Table IV Comparing systems without indexers, no partitions
Cores |  Spatial-Spark Partitioned Spatial Join | STARK w/o Indexer | GeoSpark w/o Indexer |  Magellan w/o Indexer
 --- | --- | --- | --- | --- 
8 | 21.22033333 | 7.448 | 5.611333333 | 18.748
16  | 16.19333333 | 7.834 | 4.978666667 | 19.655
24 | 18.03566667 | 6.451333333 | 5.341666667 | 18.221
          
### Table V Comparing systems without indexers, 8 partitions
Cores |  Spatial-Spark Partitioned Spatial Join  | STARK w/o Indexer | GeoSpark w/o Indexer
 --- | --- | --- | ---
8  | 9.966 | 2.502666667 | 2.289333333 
16 | 8.49967 |  2.581333333 | 1.995333333 
24 | 8.388 | 2.029666667 | 2.548 
          
### Table VI Comparing systems without indexers, 16 partitions     
Cores |  Spatial-Spark Partitioned Spatial Join  | STARK w/o Indexer | GeoSpark w/o Indexer
 --- | --- | --- | ---
8 |  5.733 | 4.453333333 | 1.462333333 
16 | 5.276 | 4.663333333 | 1.468333333 
24 | 4.99467 | 3.623333333 | 1.566666667 
