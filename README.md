This is forked from pjreddie/darknet
Simple Realtime Yolo detection with geolocation enabled by using gpsd
Installation (you must enabled gpu and opencv)
clone this repository and go to dir
make

for data, cfg, weights input and classes you wish to predict you can change it on detectclass.sh
you can change your classname output on ./detectout.sh

use./detectclass.sh for realtime detection from webcam
use ./detectout.sh to create detected object output with lattitude and longitude (txt format)
