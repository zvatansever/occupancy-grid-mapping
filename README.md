
# RoboND-OccupancyGridMappingAlgorithm

### Compiling
```sh
$ cd /home/workspace/
$ git clone https://github.com/zvatansever/occupancy-grid-mapping
$ cd occupancy-grid-mapping
$ rm -rf Images/* #Delete the folder content and not the folder itself!
$ g++ main.cpp -o app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```

### Running
```sh
$ ./app
```

Now, wait for the program to generate the map!

### Generated Map

![alt text](Images/Map.png)

