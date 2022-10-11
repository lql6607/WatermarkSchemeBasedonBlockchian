# Video Watermark Scheme using Blockchian
## Video watermarking scheme based on DWT and SVT
This repo provides the implementation of paper “A discrete wavelet transform and singular value decomposition-based digital video watermark method”.
* MATLAB:.\MinimumDistortionCost\EmbeddedAndExtractMain_clean.m  
In the folder“.\MinimumDistortionCost”， we list all the data files involved in this paper.
## Video watermarking scheme based on Blockchian
This repo provides the implementation of paper “An Efficient Video Watermark Method Using Blockchain”, which is an improved version of paper “A discrete wavelet transform and singular value decomposition-based digital video watermark method”.
* MATLAB:.\MinimumDistortionCost\EmbeddedAndExtractMain_clean.m
  * Note that, the variable "aim_index{1,countScene_i}{countKeyFrame_i}" at line 137 in the file "EmbeddedAndExtractMain_clean.m" needs to be replaced by "our_coord_{countScene_i}_{countKeyFrame_i}.mat" in ".\Blockchain\Aim_coords" accordingly.
  * All of the target coefficient coordinates in ".\Blockchain\Aim_coords" can be generated by the ".\Blockchain\main_all.m."
## Citation
> @article{liu2020video,  
>> Author = {Liu, Qingliang and Yang, Shuguo and Liu, Jing and Xiong, Pengcheng and Zhou, Mengchu},  
>> ISSN = {0307-904X},  
>> Journal = {Applied Mathematical Modelling},  
>> Pages = {273 - 293},  
>> Title = {A discrete wavelet transform and singular value decomposition-based digital video watermark method},  
>> Volume = {85},  
>> Year = {2020}  
>}
