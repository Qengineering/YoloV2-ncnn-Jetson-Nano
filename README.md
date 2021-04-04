# YoloV2-ncnn-Jetson-Nano
![output image]( https://qengineering.eu/images/test_parkV2.jpg )
## YoloV2 with the ncnn framework. <br/>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
Paper: https://arxiv.org/pdf/1612.08242.pdf<br/><br/>
Special made for a Jetson Nano see [Q-engineering deep learning examples](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html)

------------

## Benchmark.
| Model  | Jetson Nano 2015 MHz | RPi 4 64-OS 1950 MHz |
| ------------- | :-------------:  | :-------------: |
| YoloV2 (416x416)      |  **10.1 FPS** | 3.0 FPS |
| YoloV3 (352x352) tiny |  17.7 FPS | 4.4 FPS |
| YoloV4 (416x416) tiny |  11.2 FPS | 3.4 FPS |
| YoloV4 (608x608) full |  0.7 FPS | 0.2 FPS |
| YoloV5 (640x640) small|  4.0 FPS | 1.6 FPS |

------------

## Dependencies.
### April 4 2021: Adapted for ncnn version 20210322
To run the application, you have to:
- The Tencent ncnn framework installed. [Install ncnn](https://qengineering.eu/install-ncnn-on-jetson-nano.html) <br/>
- Code::Blocks installed. (`$ sudo apt-get install codeblocks`)

------------

## Installing the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/YoloV2-ncnn-Jetson-Nano/archive/refs/heads/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip, LICENSE and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm LICENSE <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
parking.jpg <br/>
busstop.jpg <br/>
YoloV2.cpb <br/>
yoloV2.cpp <br/>
mobilenet_yolo.bin <br/>
mobilenet_yolo.param <br/><br/>

------------

## Running the app.
To run the application load the project file YoloV2.cbp in Code::Blocks.<br/> 
Next, follow the instructions at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn).<br/><br/>
Many thanks to [nihui](https://github.com/nihui/) again!<br/>
![output image]( https://qengineering.eu/images/test_busV2.jpg )

