# GeoSpatial-Distributed-Systems
This repository is to provide results for experimental evaluation of state-of-the-art geospatial distributed systems

Implementing Jackpine's Micro Benchmark we have implemented the following experiments:

# Topological relations, all pair joins
Operation | Description | Query | Link
--- | --- | --- | ---
Equals | Polygon equals polygon | Find the polygons that are spatially equal to other polygons in arealm_merge table | [Polygon equals polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/polygonEqualsPolygon.md)
Equals | Point equals point | Find the points that are spatially equal to other points in pointlm_merge table | [Point equals point](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/pointEqualsPoint.md)
Disjoint | Polygon disjoint polygon | Find the polygons that are spatially disjoint from other polygons in arealm_merge table | [Polygon disjoint polygon ](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/polygonDisjointPolygon.md)
Intersects | Line intersects polygon | Find the lines in edges_merge table that intersect polygons in arealm_merge table | [Line intersects polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/lineIntersectsPolygon.md)
Intersects  | Point intersects polygon | Find the points in pointlm_merge table that intersect polygons in arealm_merge table | [Point intersects polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/pointIntersectsPolygon.md)
Intersects | Point intersects line | Find the points in pointlm_merge table that intersect lines in edges_merge table | [Point intersects line](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/pointIntersectsLine.md)
Intersects | Line intersects line | Find the lines that intersect lines in edges_merge table| [Line intersects line](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/lineIntersectsLine.md)
Touches | Polygon touches polygon | Find the polygons that touch polygons in arealm_merge table | [Polygon touches polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/polygonTouchesPolygon.md)
Touches | Line touches polygon | Find the lines in edges_merge table that touch polygons in arealm_merge table | [Line touches polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/lineTouchesPolygon.md)
Crosses | Line crosses line | Find first 5 lines that crosses other lines in edges_merge table | [Line crosses linelineCrossesLine](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/lineCrossesLine.md)
Crosses | Line crosses polygon | Find the lines in edges_merge table that cross polygons in arealm_merge table | [Line crosses polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/lineCrossesPolygon.md)
Overlaps | Polygon overlaps polygon | Find the polygons that overlap other polygons in arealm_merge table | [Polygon overlaps polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/polygonOverlapsPolygon.md)
Overlaps | Line overlaps polygon | Find the lines in edges_merge that overlap polygons in arealm_merge table | [Line overlaps polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/lineOverlapsPolygon.md)
Within | Polygon within polygon | Find the polygons that are within other polygons in arealm_merge table | [Polygon within polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/polygonWithinPolygon.md)
Within | Line within polygon | Find the lines in edges_merge table that are inside the polygons in arealm_merge table | [Line within polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/lineWithinPolygon.md)
Within | Point within polygon | Find the points in pointlm_merge table that are inside the polygons in arealm_merge table | [Point within polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/pointWithinPolygon.md)
Contains | Polygon contains polygon | Find the polygons that contain other polygons in arealm_merge table | [Polygon contains polygon](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/polygonContainsPolygon.md)
Contains | Polygon contains point | Find the polygons in arealm_merge that contain points in pointlm_merge table | [Polygon contains point](https://github.com/kgiann78/GeoSpatial-Distributed-Systems/blob/master/polygonContainsPoint.md)
