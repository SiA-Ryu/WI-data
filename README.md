# WI-data
Utilizing the public digital elevation model provided by the National Geographic Information Institute, in conjunction with Skyview by Naver Map, we executed a comprehensive simulation within an real urban setting.
Employing the Wireless Insite ray tracing tool, we meticulously quntifierd the Reference Signal Received Power (RSRP) dynamics through a controlled movement along a determined route, within an environment housing a cluster of five BSs.

In each csv file, we compiled RSRP dataset originating from five BSs.

Rows represent each point in the moving route and it consists of a totla of 824 points.

Columns represent 256 possible beam indices formed by 16x16 antenna. For the horizontal and vertical beam index h x v of the antenna, Beam 1 ~ Beam 16 represent 1 x 1 ~ 1 x 16, Beam 17 ~ Beam 32 represent 2 x 1 ~ 2 x 16, ..., Beam 241 ~ Beam 256 represent 16 x 1 ~ 16 x 16.

Each value is the measured RSRP when the corresponding beam is used at each point. The unit of values is [dBm].
