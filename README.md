This package built a STDR simulation enviroment

### **node_name**: 
- **driver_node**

### **para_name**:
- **wall_dist**:It is the distance to the wall, where the stop is an ideal parameter that can be retrieved from the parameter server.

- **robot_ns**:This variable determines the namespace of the subscriber_node; the default value is robot0

In launch file robot_supervisor.launcharg name="robot_ns"is used to set the namespace of node with the default of robot0. You can change the namespace with this arg.
