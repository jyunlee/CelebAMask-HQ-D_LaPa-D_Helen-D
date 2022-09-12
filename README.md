# CelebAMask-HQ-D / LaPa-D / Helen-D

## Face Parsing From RGB and Depth Using Cross-Domain Mutual Learning (CVPRW 2021) ##

Jihyun Lee, Binod Bhattarai, Tae-Kyun (T-K) Kim

**[\[Paper\]](https://openaccess.thecvf.com/content/CVPR2021W/AMFG/html/Lee_Face_Parsing_From_RGB_and_Depth_Using_Cross-Domain_Mutual_Learning_CVPRW_2021_paper.html)**


![alt text](https://github.com/jyunlee/CelebAMask-HQ-D_LaPa-D_Helen-D/blob/main/images/img.jpg)

> Existing methods of face parsing have proven effective at classifying each pixel of an RGB image into different facial components. However, there is a lack of face parsing research that utilizes depth domain. To the best of our knowledge, we present the first study to exploit 2.5D data for face parsing. We introduce a novel framework to jointly learn (1) RGB face parsing, (2) depth face parsing and (3) RGB-to-depth domain translation, which can be effective even when only a small amount of annotated depth data is available for training. To this end, we also create the first RGB-D face parsing benchmarks based on CelebAMask-HQ, LaPa and Helen by utilizing an off-the-shelf 3D head reconstruction model. Overall, our approach makes two main contributions. First, our method leverages mutual learning between RGB and depth face parsing, which enables bidirectional knowledge distillation between the two data domains. Second, our method utilizes end-to-end learning of RGB-to-depth domain translation and depth face parsing, which can help overcome the scarcity of annotated depth data. We perform extensive experiments to validate the effectiveness of our method, in which we achieve state-of-the-art results in RGB face parsing. As far as we know, we also report the first results on face parsing from depth data.

&nbsp;
&nbsp;

## CelebAMask-HQ-D
1. Download RGB images and annotations from [the official CelebAMask-HQ repository](https://github.com/switchablenorms/CelebAMask-HQ).
2. Download `CelebAMask-HQ-D.zip`  from [this Google Drive link](https://drive.google.com/drive/folders/1NuQAmLgxzE7w2yIW4jBnAie3sj7Su03Y?usp=sharing). Extract the zip file to obtain our depth images.

## LaPa-D
1. Download RGB images and annotations from [the official LaPa repository](https://github.com/JDAI-CV/lapa-dataset).
2. Download `LaPa-D.zip`  from [this Google Drive link](https://drive.google.com/drive/folders/1NuQAmLgxzE7w2yIW4jBnAie3sj7Su03Y?usp=sharing). Extract the zip file to obtain our depth images.

## Helen-D
1. Download RGB images and annotations from [the official Helen website](http://www.ifp.illinois.edu/~vuongle2/helen/).
2. Download `Helen-D.zip`  from [this Google Drive link](https://drive.google.com/drive/folders/1NuQAmLgxzE7w2yIW4jBnAie3sj7Su03Y?usp=sharing). Extract the zip file to obtain our depth images.

&nbsp;

## Citation
If you find this work useful, please consider citing our paper.
```
@inproceedings{lee2021face,
  title={Face parsing from RGB and depth using cross-domain mutual learning},
  author={Lee, Jihyun and Bhattarai, Binod and Kim, Tae-Kyun},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops},
  year={2021}
}
```

&nbsp;

## Acknowledgements

We sincerely appreciate the authors of the original `CelebAMask-HQ` , `LaPa` and `Helen` benchmarks, which our work is mainly based on. If you find our work useful, please also consider citing these papers:

#### CelebAMask-HQ [Lee *et al.*, CVPR 2020]
```
@inproceedings{CelebAMask-HQ,
  title={MaskGAN: Towards Diverse and Interactive Facial Image Manipulation},
  author={Lee, Cheng-Han and Liu, Ziwei and Wu, Lingyun and Luo, Ping},
  booktitle={CVPR},
  year={2020}
}
```

#### LaPa [Liu *et al.*, AAAI 2021]
```
@inproceedings{liu2020new,  
  title={A New Dataset and Boundary-Attention Semantic Segmentation for Face Parsing.},  
  author={Liu, Yinglu and Shi, Hailin and Shen, Hao and Si, Yue and Wang, Xiaobo and Mei, Tao},  
  booktitle={AAAI},  
  year={2020}  
}
```

#### Helen [Le *et al.*, ECCV 2012]
```
@inproceedings{le2012interactive,
  title={Interactive facial feature localization},
  author={Le, Vuong and Brandt, Jonathan and Lin, Zhe and Bourdev, Lubomir and Huang, Thomas S},
  booktitle={ECCV},
  year={2012},
}
```
