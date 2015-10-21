
#### Package Contents

#####./lasa-robots/kuka_lwr_bringup/launch/  
- lwr2_realtime_viz.launch (main launcher which starts the robot_state_publisher topic)
- lwr2_loopback_sim_no_controllers.launch (intermediate configuration launcher)
- upload_lwr2.launch (model starter and updater)
- world_to_camera_tf_broadcaster_dataset.launch (world to cameras transformation)

#####./lasa-robots/kuka_lwr_bringup/models/  
- /table/table2.urdf.xacro (main table supporting robot)
- /table/operation_table.urdf.xacro (table where task is taking place)
- /pole/pole.urdf.xacro (kinect camera pole)
- /pole/pole2.urdf.xacro (kinect2 camera pole)

#####./lasa-robots/kuka_lwr_description/robots/  
- kuka_lwr2_lasa.urdf.xacro (main file to include all models and transformations)
