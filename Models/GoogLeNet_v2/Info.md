## GoogLeNet v2
* Model File (compressed) - [GoogLeNet v2](Models/GoogLeNet_v2/GoogLeNet_v2.tar.gz) 
* Input Size - *Batchx3x224x224*
* Classes - [Classes File - Torch Format](https://github.com/eladhoffer/ImageNet-Training/raw/master/ImageNetClasses)
* Global Normalization (mean, std) - *118.380948, 61.896913*
* Dependencies - *cudnn*
* Validation Loss: *1.372*
* Validation Top1: *0.6893*
* Validation Top5: *0.8982*
* Training Configuration - [Using "ImageNet-Training"](https://raw.githubusercontent.com/eladhoffer/ImageNet-Training/master/Models/GoogLeNet_BN_Original.lua) (Batch normalization removed post training)
* Original Paper - [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](http://arxiv.org/abs/1502.03167)
