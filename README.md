# DeepLung

## References: 
  Zhu, Wentao, Chaochun Liu, Wei Fan, and Xiaohui Xie. "DeepLung: Deep 3D Dual Path Nets for Automated Pulmonary Nodule Detection and Classification." IEEE WACV, 2018.
  
  https://github.com/wentaozhu/DeepLung
  

## Dependecies: 
  Ubuntu 18.04, CUDA 11.0, cudnn 7.6.5, NVIDIA driver 451.67</br>
  python 3.7.7, pytorch (1.5.1)</br>
  h5py (2.10.0), matplotlib (3.3.0), numpy (1.18.5), nvidia-ml-py (7.352.0), pandas (10.05)</br>
  pyparsing (2.4.7), scikit-image (0.17.2), scipy (1.4.1)</br>
  SimpleITK (1.2.4)</br>

## Docker image
  https://hub.docker.com/repository/docker/morpheus9631/jupyter

## Download 
  LUNA16 dataset from https://luna16.grand-challenge.org/data/  
  LIDC-IDRI dataset from https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI

## Results:

<img src="https://user-images.githubusercontent.com/23013229/104151044-e56be800-5416-11eb-805e-2d6882003dfd.png" width="800">

<img src="https://user-images.githubusercontent.com/23013229/104151403-e8b3a380-5417-11eb-8343-940487488220.png" width="800">

### CAD Analysis:
　Candidate detection results:</br>
　　True positives: 985 </br>
　　False positives: 2649 </br>
　　False negatives: 67 </br>
　　True negatives: 0 </br>
　　Total number of candidates: 5686 </br>
　　Total number of nodules: 1052 </br>
　　Ignored candidates on excluded nodules: 2010 </br>
　　Ignored candidates which were double detections on a nodule: 42 </br>
　　Sensitivity: 0.936311787 </br>
　　Average number of candidates per scan: 6.403153153 </br>

</br>
<img src="https://user-images.githubusercontent.com/23013229/103987393-616ff100-51c7-11eb-9e13-4e5786509c47.png" width="800">

