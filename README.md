# WI-data
Utilizing the public digital elevation model provided by the National Geographic Information Institute, in conjunction with Skyview by Naver Map, we executed a comprehensive simulation within an real urban setting.
Employing the Wireless Insite ray tracing tool, we meticulously quntifierd the Reference Signal Received Power (RSRP) dynamics through a controlled movement along a determined route, within an environment housing a cluster of five BSs.

In each csv file, we compiled RSRP dataset originating from five BSs.

Rows represent each point in the moving route and it consists of a total of 824 points.

Columns represent 256 possible beam indices formed by 16x16 antenna configuration. 
The h x v denotes the beam index along the horizontal and vertical directions, and 'Beam f' indicated in the label of the csv file's columns is calculated as f = 16 x (h - 1) + v.

Each value is the measured RSRP when the corresponding beam is used at each point. The unit of values is [dBm].
