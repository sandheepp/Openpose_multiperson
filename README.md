# About the Project
This is a part of a project which detects people from a video frame.

# Requirements : 
1. OpenCV > 3.4.1
2. Matplotlib for Notebook
3. RUN getModels.sh from command line Or Download caffe model from http://posefs1.perception.cs.cmu.edu/Users/ZheCao/pose_iter_440000.caffemodel and put it in pose/coco folder


# Compiling Cpp file

## Using G++:
Command to compile the cpp file in ubuntu:
```
g++ -o3 -std=c++11 multi-person-openpose.cpp `pkg-config --libs --cflags opencv` -lpthread -o multi-person-openpose
```

## Using CMake:

```
cmake .
make
```

# Usage
1. Python
```
python multi-person-openpose.py
```

2. C++
```
./multi-person-openpose
```
