# Calibration
This repository contains some codes which calibrate camera by opencv2.4.10.

What is calib class?
-------------------

このクラスはtake_chessクラスで作られたxmlファイルをもとにカメラキャリブレーションを行い、その結果と、各種パラメーターの値が書き込まれたxmlファイルを出力するためのものです。

First, this class is provided xml file generated by take_chess class before, then calibrates camera and export xml file which contains some parameters used in undistorting.


Execution check environment
---------------------------

windows8.1 64bit	
vc12	
win32 console application	
opencv2.4.10	

License
-------

Source codes are under GPLv3.