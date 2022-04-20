=============================================================
Datasets used for CVPR18 paper:
Recovering Realistic Texture in Image Super-resolution by
        Deep Spatial Feature Transform
    Xintao Wang, Ke Yu, Chao Dong, Chen Change Loy
=============================================================

For more information, please visit the project website and see Supplementary Material:
    http://mmlab.ie.cuhk.edu.hk/projects/SFTGAN/
OR visit our github repo:
    https://github.com/xinntao/CVPR18-SFTGAN

If you use the dataset in a publication, please cite our paper below:
@inproceedings{wang2018sftgan,
    author = {Xintao Wang, Ke Yu, Chao Dong and Chen Change Loy},
    title = {Recovering Realistic Texture in Image Super-resolution by Deep Spatial Feature Transform},
    booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year = {2018}
}

========================
File Information
========================

- OutdoorSceneTrain
    10,324 images of outdoor scenes for training.
    It is collected by querying images from search engines using the defined categories.
    It is divided into 7 categories:

    -      sky:  1,727
    -    water:    857
    - building:  2,285
    -    grass:  1,140
    -    plant:  1,036
    -   animal:  2,187
    - mountain:  1,092
    -    Total: 10,324


- OutdoorSceneTest300 (OST300)
    300 images of outdoor scenes for testing.
    It is used in both segmentation evaluation and SR evaluation.

    - OST300_img.zip: original images
    - OST300_anno.zip: segmentation annotations


- OutdoorSeg
    A newly merged training dataset for outdoor scene segmentation.
    9,900 images, where 8,447 images from ADE dataset, 899 mountain images from Flickr website and 554 animal images from COCO dataset.

    - OutdoorSeg_img.zip: original images
    - OutdoorSeg_anno.zip: segmentation annotations


- ImageNet_list.txt
    list of ImageNet validation images for pretraining our SR model.
    Removing low resolution images of size below 30kB in ImageNet validation dataset.
    452748 records. The format is:
    "
    n01440764/n01440764_10040.JPEG
    n01440764/n01440764_10048.JPEG
    ...
    "

========================
Notes
========================

- annotation table
    - 0, background
    - 1, sky
    - 2, water
    - 3, grass
    - 4, mountain
    - 5, building
    - 6, plant
    - 7, animal
    - 255(8), void

=========================
Contact
=========================

Please contact Xintao Wang (wx016@ie.cuhk.edu.hk) for questions about the dataset.