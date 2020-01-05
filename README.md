# keras-faceDetection

This repositry for face detection program using keras.
(Refarence: http://wisteriahill.sakura.ne.jp/CMS/WordPress/2019/06/29/raspberry-pi-face-emotion-classification/)

## OS/Soft Ware
- Raspbian 10(buster)
- Python3.7

## Package
- Tensorflow(1.14.0)
- keras(2.3.1)
- Open CV(3.2.0)
- picamera(Option)

## How to Setup
- Using Web Cam
  
  ```
  $ sudo apt-get install libblas-dev liblapack-dev python3-dev libatlas-base-dev gfortran python3-setuptools python3-numpy
  $ sudo apt-get install python3-opencv
  $ sudo pip3 install tensorflow
  $ sudo apt-get install python3-h5py
  $ sudo apt-get install python3-pandas
  $ sudo pip3 install matplotlib
  $ sudo pip3 install keras
  ```
- Using Picamera
  - Same setting of Web Cam
  - In addition, run commands below
  ```
  $ pip3 install picamera
  $ pip3 install "picamera[array]"
  ```
## How to run
Move code directory

```
$ cd src
```
If you run detect emotion, run ```python3 video_emotion_color_demo.py```.
