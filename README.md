[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/full-resolution-network-and-dual-threshold/retinal-vessel-segmentation-on-drive)](https://paperswithcode.com/sota/retinal-vessel-segmentation-on-drive?p=full-resolution-network-and-dual-threshold)[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/full-resolution-network-and-dual-threshold/retinal-vessel-segmentation-on-chase_db1)](https://paperswithcode.com/sota/retinal-vessel-segmentation-on-chase_db1?p=full-resolution-network-and-dual-threshold)
# FR-UNet
This repository is the official PyTorch code for the paper 'Full-Resolution Network 
and Dual-Threshold Iteration for Retinal Vessel and Coronary Angiograph Segmentation' 
(Wentao Liu, Huihua Yang, Tong Tian, Zhiwei Cao, Xipeng Pan, Weijin Xu and Yang Jin)


<div align="center">
  <img src="figs/FR-UNet.png" width="100%">
</div>

 
## Prerequisites
 

 
Download the repo:
```
git clone <repo link>
cd RF-UNet
```
Install packages from requirements.txt
```
pip install -r requirements.txt
```

Process the data
data_process.py file
 
```
python data_process.py -dp DATASET_PATH -dn DATASET_NAME
```
 
## Training
Type this in terminal to run the train.py file
 
```
python train.py -dp DATASET_PATH
```
## Test
Type this in terminal to run the test.py file
 
```
python test.py -dp DATASET_PATH -wp WEIGHT_FILE_PATH
```
The weights are in the trained-weights folder
```
python test.py -dp DATASET_PATH -wp trained-weights/DATASET_NAME
```


 
## License
 
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
 
