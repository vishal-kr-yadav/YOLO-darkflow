download cython locally

cd Cython-0.28.1/
python setup.py install

cd darkflow-master/
python setup.py build_ext --inplace
python flow --model cfg/yolo.cfg --load bin/yolo.weights --demo videofile.mp4 --saveVideo (error)

pip3 install tensorflow

pip3 install opencv-python


python flow --model cfg/tiny-yolo-1c.cfg --load bin/yolo.weights --train --annotation new_model_data/annotations --dataset new_model_data/images --epoch 15
