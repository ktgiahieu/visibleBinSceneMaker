# Bin Picking Simulation

## Video
[![Video(YouTube)](https://img.youtube.com/vi/v7mqrS9xTY4/0.jpg)](https://youtu.be/v7mqrS9xTY4)

## Abstract
This program helps to construct 3D scene for the bin picking based on the 3D pointcloud of an object.

The project takes a .STL mesh model as an input, then it will create a synthetic scene using [Point Cloud Library(PCL)](http://pointclouds.org/) for pointcloud processing and [Bullet Physics](http://bulletphysics.org/wordpress/) for physics simulation.

A poster in ROBOMECH 2017, "Development of program for generating pointcloud of bin scene using physical simulation and perspective camera model," introduces this programs.
These programs help to construct 3D recognition algorithms for the bin picking based on the 3D pointcloud.

# Requirements

## Linux

To build this project you will need:

* Point Cloud Library ([PCL](https://pointclouds.org/downloads/#linux)) 
    ```
    $ sudo apt install libpcl-dev

* cmake

* Bullet3 (which is already compiled with the project)


### Compile and run
```
    mkdir build
    cd build
    cmake ..
    make
    ./binSceneMaker
```


## Windows
To build this project you will need:

* Visual Studio 2017

* [OpenNI2](https://s3.amazonaws.com/com.occipital.openni/OpenNI-Windows-x64-2.2.0.33.zip) 

* Point Cloud Library ([PCL 1.9.1](https://github.com/PointCloudLibrary/pcl/releases/download/pcl-1.9.1/PCL-1.9.1-AllInOne-msvc2017-win64.exe)) 

Install PCL as you wish, just don't install OpenNI2 at this stage


![Result](https://github.com/ktgiahieu/BinPickingSimulation/blob/main/images/PCL.png)

* cmake 3.18.5

* Bullet3 (which is already compiled with the project)

## License

The license of these programs is MIT License.
Please use follows as your references.

> Naoya Chiba and Koichi Hashimoto. "Development of program for generating pointcloud of bin scene using physical simulation and perspective camera model." The Robotics and Mechatronics Conference 2017(ROBOMECH 2017), 2A2-O09, Fukushima, May, 12th, 2017.

> 千葉 直也，橋本 浩一．物理シミュレーションと透視投影カメラモデルを用いたバラ積みシーン点群生成プログラムの開発．ロボティクス・メカトロニクス講演会2017(ROBOMECH 2017)，2A2-O09，福島，5月12日，2017．
