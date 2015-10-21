# Recording of Demonstrations from Multiple Sensors
Launch files and for startup/visualization/recording of Kinect 1 + Kinect 2 + Mocap + KUKA Robot 
kit to record videos for the dataset

### Package content:

The package contains launchers and visualization models for the data acquisition:  
#####./record-demo-multi-sensors/launch/  
- dataset.sh
- dataset_bag.sh
- dataset.launch
- dataset_bag.launch
- rviz_dataset.launch


### Quick steps:

1 - go to the directory where launchers are  
% to run the capture  
2 - execute command: ./dataset.sh  
% to start recording (when executed follow instructions to enter the name of the session)  
3 - execute command: ./dataset_record.sh



### Notes:  
you may want to change the path where records will be saved, then edit "dataset_record.sh" files and change lines #26 - #28  
- You will need robot-mirror package to start robot node (./launch/robot_mirror.launch)   
- Launch rviz to visualize your own configuration. That can be changed in rviz_dataset.launch file  
