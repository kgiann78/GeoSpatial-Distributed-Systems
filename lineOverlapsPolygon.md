# Line Overlaps Polygon

### Comparing systems with indexers, no partitions
  Cores | Exareme SpatialIndex | Spatial Spark Broadcast Spatial Join | GeoSpark Indexed
--- | --- | --- | ----
  8 | 43.72133333 | 28.9673 | 153.0473333
  16 | 43.31733333 | 21.186 | 
  24 | 43.713 | 22.5777 | 

### Comparing systems with indexers, 8 partitions
  Cores | Exareme SpatialIndex |  Spatial Spark Broadcast Spatial Join  | GeoSpark Indexed
--- | --- | --- | ----
  8 | 13.437  | 28.0183 |  
  16 | 13.09566667  | 21.9503 | 143.327
  24 | 14.256 |  19.3307 | 127.7576667 

### Comparing systems with indexers, 16 partitions
  Cores | Exareme SpatialIndex | Spatial Spark Broadcast Spatial Join | GeoSpark Indexed
--- | --- | --- | ----
  8 | 14.64333333 | 28.5523 | 161.2096667 
  16 | 14.97733333 | 20.3847 | 105.4203333
  24 | 14.29566667 | 24.9103 | 

### Spatial Spark without indexers
  Cores | Spatial Spark Partitioned Spatial Join 64 partitions| Spatial Spark Partitioned Spatial Join 256 partitions| Spatial Spark Partitioned Spatial Join 512 partitions  
--- | --- | --- | ---
  8 | 222.878 | 171.346 | 180.521 
  16 | |    135.5 | 130.491  
  24 | |  149.45  | 119.093  

### GeoSpark without indexer
  Cores | GeoSpark No Partitions | GeoSpark 8 Partitions | GeoSpark 16 Partitions  
--- | --- | --- | ----
  8 | 1144.688333 | | 365.7136667 
  16 | 1049.238 | 1237.103667 | 356.5803333 
  24 | 1078.862333 | 1469.978333 | 402.1166667 
