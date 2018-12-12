# face2face-dwayne
using pix2pix-tensorflow

git clone git@github.com:DineshRajanT/face2face-dwayne.git


python generate_train_data.py --file video-file.mp4 --num 400 --landmark-model shape_predictor_68_face_landmarks.dat

video-file is the name of the video file from which you want to create the data set.
num is the number of train data to be created.
landmark-model is the facial landmark model that is used to detect the landmarks.
