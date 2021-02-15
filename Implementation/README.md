# Description  
- All model architecture and training/testing setting implemented as close as possble to the paper  
- Results are shown inside the inidividual directories :)

## VGG  
1. Comparison between CIFAR-10 and imagewoof dataset training  
2. Slight modification to the VGG models when deemed appropriate for the dataset  
3. Altered VGG is VGG without padding so the spacial resolution decreases each CNN layer  
4. pretrained with VGG-A, then continued training with VGG-D as in the paper (can be replaced with Xavier Init)
5. Work on Colab 

## ResNet
1. Comparison of Basic Block vs Bottleneck in ResNet18
2. Uses imagenette2
3. Implemetation allows switching from shortcut type 'A', 'B', and 'mine' which I tried making  
4. Work on Colab  
5. Added comparison to other types

## CAM  
1. Tried using ResNet18 with 'B' shortcut  
2. The a layer in the last BuildingBlock has its stride altered from 2 to 1 to maintain mapping resolution as 14 x 14  
3. Work on Colab  

## Grad-CAM  
1. Changed the CAM implementation to do Grad-CAM  
2. Comparison between CAM and Grad-CAM  
3. Work on Colab  

## STN (work in progress)  
1. SVHN dataset with ST-CNN Single  
2. Slight modification due to different image size to the ones used for the paper  
3. Implementation halfway done for shift from single classification to multi-digit recognition  
4. Work on Colab  
