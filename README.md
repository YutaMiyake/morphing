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

## References
- https://github.com/spmallick/learnopencv/blob/master/FaceMorph/faceMorph.py
- https://www.learnopencv.com/face-morph-using-opencv-cpp-python/#id2374336389
