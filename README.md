# Grasp-Deep-Learning Workspace

This ROS workspace encompasses the Grasp-Deep-Learning project. 
Run the following to initialize/update your workspace:
```wstool update```

To set all enviornment variables run:
```source setup.bash```

Generating data:
* Run ```python get_big_bird_models.py``` in *gazebo_data_gen_gdl/src/gazebo_simulate_kinect*
* Run the grasp generator in *graspit_gdl/bin/graspit* using the downloaded models
* Run ```python build_training_data2.py``` to generate the h5 datasets from the generated grasps
* Something goes here...
* Run ```python train_convnet.py```


## This workspace contains:
* [Gazebo_data_gen_gdl](https://github.com/CURG/gazebo_data_gen_gdl)
* [graspit_gdl](https://github.com/CURG/graspit_gdl)
* [ivcon_gdl](https://github.com/CURG/ivcon_gdl)
* [pylearn2](https://github.com/CURG/pylearn2)
* [pylearn_classifier_gdl](https://github.com/CURG/pylearn_classifier_gdl)
* [saxena_dataset_gdl](https://github.com/CURG/saxena_dataset_gdl)
