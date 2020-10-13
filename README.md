# Image-to-Image translation with U-GAT-IT (20200902 ~ 20201008)  
- This project is designed to implement U-GAT-IT by using GHIBLI character image dataset.  
- This repo is maintained by [최우철](https://github.com/choiwoochul), [조한별](https://github.com/STAR3073), [허지혜](https://github.com/jihyeheo), [이수빈](https://github.com/I-SUBIN), 오서영, [최연석](https://github.com/YeonSeok-Choi), [강수연](https://github.com/Kangsooyeon)

[[Presentation]](https://github.com/OH-Seoyoung/Image-to-Image_translation_with_U-GAT-IT/blob/master/presentation.pdf)  

## Dataset
#### Character Images
- We capture about 1000 GHIBLI female character images in 7 Ghibli studio movies.  
#### Female Images
- selfie2anime dataset from https://github.com/taki0112/UGATIT  
<div align="center">  
<img src="https://github.com/OH-Seoyoung/Image-to-Image_translation_with_U-GAT-IT/blob/master/Figure/dataset.jpg" width="65%"> <br>
</div>

## Architecture  
#### Generator and Discriminator  
<div align="center">
<img src="https://github.com/OH-Seoyoung/Image-to-Image_translation_with_U-GAT-IT/blob/master/Figure/architecture1.jpg" width="45%">
<img src="https://github.com/OH-Seoyoung/Image-to-Image_translation_with_U-GAT-IT/blob/master/Figure/architecture2.jpg" width="45%"> <br>
</div>  

#### Loss Function  
<div align="center">
<img src="https://github.com/OH-Seoyoung/Image-to-Image_translation_with_U-GAT-IT/blob/master/Figure/architecture3.jpg" width="50%"> <br>
</div>  

## Results  
<div align="center">
<img src="https://github.com/OH-Seoyoung/Image-to-Image_translation_with_U-GAT-IT/blob/master/Figure/result.jpg" width="65%"> <br>
</div>  

## Reference  
'''
- Original code : https://github.com/taki0112/UGATIT
- Kim, Junho, et al. "U-gat-it: unsupervised generative attentional networks with adaptive layer-instance normalization for image-to-image translation." arXiv preprint arXiv:1907.10830 (2019).
'''
