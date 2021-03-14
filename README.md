[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# RoboND-MinkowskiSum
Inflate any obstacle and generate its configuration space using the Minkowski Sum.

### Example
Generating the configuration space of the blue Robot and red Obstacle

![alt text](images/Minkowski_Sum_Initial.png)

### Compiling
```sh
$ cd <repo_root>
$ mkdir build && cd build
$ cmake ..
$ make
```

### Running
```sh
$ cd <repo_root>/bin
$ ./minkowski_sum
```

### Generated Configuration Space
This program will first translate the blue robot position to the red obstacle, generate the green configuration space of the blue robot and red obstacle, and translate it to the red obstacle position as follows:

![alt text](images/Minkowski_Sum_NonShifted.png)

![alt text](images/Minkowski_Sum_Final.png)
