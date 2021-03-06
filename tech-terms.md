# BC Route Planner
# Technical Terms
Term | Definition
----: | -----------
<a name="Contraction Hierarchies">Contraction Hierarchies</a> | A preprocessing technique to speed up shortest route calculation over large road networks. During preprocessing, short cuts are added to the road network and nodes are ordered to reflect the depth of the shortcuts. Edge weights are static when computing short-cut weights.
<a name="Contraction Hierarchies">Customizable Contraction Hierarchies</a> | A technique to extend Contraction hierarchies to support changing road conditions and user preferences. Preprocessing is divided into three phases. In the first expensive phase, short cuts are computed based solely on the topology of the road network. In the second, much less expensive phase, short cuts are computed based on updated road conditions (e.g., road or lane closures, traffic congestion). In the third phase, short cuts are computed based on user preferences. 
<a name="Edge weight">Edge weight</a> | Travel time a vehicle needs to traverse the edge (road).
<a name="Time-dependent routing">Time-dependent routing</a> | The earliest arrival problem in road networks with time-dependent functions as edge weights.

