# Introduce
- Image base on alpine 3.9
- Anaconda3
- Packages: opencv scikit-learn matplotlib scipy pillow pandas dlib  face_recognition_models dlib
- Support GPU

# Build
docker build -t "tag_name" .

# How to run
dokcer run -it bienkma/dlib-gpu-cuda7.5-alpine-anaconda3 --name dlib-gpu sh
