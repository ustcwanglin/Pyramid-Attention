Code for "Spatial-Temporal Pyramid Attention ConvLSTM Network for Action Recognition" 

We propose a spatial pyramid module to take full use of inherent multi-scale 
information of CNNs. 
To capture more comprehensive long-range temporal 
structure, we also propose a new temporal pyramid module in which frame-level 
features are reused by various pooling approaches to get different 
time-grained features of snippets efficiently. 


## Prerequisites
1) Python 2.7
2) Tensorflow-1.2 <br/>

## Get the pretrained models
The trained models can be obtained from the below link: 
    Link: https://pan.baidu.com/s/17xtNvmLR5kXjkoKzYXyDpw  Code: f820 

## How to use the code
### Prepare the data
UCF-101
Download videos and convert from avi to jpg files using Datasets/ucf_video_to_images.py

HMDB-51
Download videos and convert from avi to jpg files using Datasets/hmdb_video_to_images.py

### Training 
1) Use training_*.py to train the networks for different datasets and different modalities. <br/>
### Testing 
1) Use testing_*.py to evaluate the trained networks on the valid or test subsets of Jester or IsoGD. <br/>

## Contact
For any question, please contact xiaquhet@mail.ustc.edu.cn 

