# camera-intrinsics

unsupervised joint learning of cam_intri, extinsics ( rotation &amp; translation) and depth for videos

Thic repository contains a copy of camera intrisics learning paper https://arxiv.org/abs/1904.04998 source code https://github.com/google-research/google-research/tree/master/depth_from_video_in_the_wild


# Requirement 
python 2 / 3

TensorFlow

CUDA





# Traning 
python train.py —data_dir=/opt/meituan/cephfs/user/hadoop-wallepnc/lixin/data/kitti/format_data_3 --checkpoint_dir=./log/2019-08-26


The --data_dir is the processed data directory where the training data (in Struct2depth's format) is stored. The data_example folder contains a single training example expressed in this format.

The chechpoint_dir is where the trained model will be saved or the model to be resume training process.



