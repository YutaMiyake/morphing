# Morphing
This jupyter notebook allows you to create mix or morphed images of two faces and gif of changing faces between one to another.

## Gallery
<img src="https://github.com/YutaMiyake/morphing/blob/master/screenshots/la_joconde_facial_features.png" width="350px"><img src="https://github.com/YutaMiyake/morphing/blob/master/screenshots/yayoi_kusama_facial_features.png" width="350px">
<img src="https://github.com/YutaMiyake/morphing/blob/master/screenshots/triangles.png" width="350px">
<img src="https://github.com/YutaMiyake/morphing/blob/master/screenshots/mix.png" width="350px">
![gif1](https://github.com/YutaMiyake/morphing/blob/master/videos/result.gif)

## Installation
- clone this repository
- get model
```
wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
bzip2 -d http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
```
- prepare two face jpeg images of same size
- prepare morphing env in your local machine
```
virtualenv -p python3.6 morphing
source ./morphing/bin/activate

pip install -r requirements.txt

./morphing/bin/ipython kernel install --user --name=moprhing
```
- run jupyter notebook
```
./morphing/bin/jupyter notebook
```

## Acknowledgements
- https://github.com/spmallick/learnopencv/blob/master/FaceMorph/faceMorph.py
- https://www.learnopencv.com/face-morph-using-opencv-cpp-python/#id2374336389
