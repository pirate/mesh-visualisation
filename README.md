**Click to add nodes!** Any existing nodes within the red circle (that is, within 30px of the cursor) will be linked to the new node.

This example was implemented in [D3](http://mbostock.github.com/d3/). D3's force-directed layout uses the Barnes-Hut approximation to compute repulsive charge forces between all nodes efficiently. Links are implemented as geometric constraints on top of position Verlet integration, offering greater stability. A virtual spring between each node and the center of the chart prevents nodes from drifting into space.