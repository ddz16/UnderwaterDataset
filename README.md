# UnderwaterDataset
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
![Stars](https://img.shields.io/github/stars/ddz16/UnderwaterDataset)

This repository contains various underwatr datasets for enhancement, detection, segmentation...

Each dataset contains the following types of data:
![Image](https://img.shields.io/badge/-Image-brightgreen)
![Video](https://img.shields.io/badge/-Video-red)
![Paired](https://img.shields.io/badge/-Paired-blue)
![RawOnly](https://img.shields.io/badge/-RawOnly-pink)
![DeepSea](https://img.shields.io/badge/-DeepSea-brown)
![Depth](https://img.shields.io/badge/-Depth-orange)
![Synthetic](https://img.shields.io/badge/-Synthetic-purple)
![Instance](https://img.shields.io/badge/-Instance-yellow)

## Some Additional Information.

🚩 **There is a [Chinese review article](https://jeit.ac.cn/article/doi/10.11999/JEIT221402?pageType=en) about underwater datasets.**

🚩 **I have found a [website](https://universe.roboflow.com/university-of-michigan-du9nk/object-detector_yihan-guo) where there are many small underwater datasets available for download.**

## Enhancement/Restoration.
Year|Dataset|Type|Pub|Description
-----|----|---|-----|-----
2019|[SQUID](https://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)![Depth](https://img.shields.io/badge/-Depth-orange)|TPAMI| It includes RAW images, TIF files, camera clibration files, and distance maps. The database contains 57 stereo pairs from four different sites.
2019|[U45](https://github.com/IPNUISTlegal/underwater-test-dataset-U45-)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)|None| A pubic underwater test dataset including 45 images suffering from the color casts, low contrast and haze-like effects of underwater degradation.
2019|[Sea-thru](https://csms.haifa.ac.il/profiles/tTreibitz/datasets/sea_thru/index.html) [Sea-thru](https://www.kaggle.com/datasets/colorlabeilat/seathru-dataset)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)![Depth](https://img.shields.io/badge/-Depth-orange)|CVPR| It includes RAW images (.ARW or .DEF files) and corresponding depth maps (.tif files).
2019|[RUIE](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)|TCSVT| It contains two subset datasets, UIQS and UCCS, which contain only raw underwater images to test UIE algorithms for the ability of improving visibility and correcting color casts, respectively.
2019|[UIEB](https://li-chongyi.github.io/proj_benchmark.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)|TIP| UIEB includes two subsets: 890 raw underwater images with corresponding high-quality reference images; 60 challenging underwater images.
2020|[EUVP](https://irvlab.cs.umn.edu/resources/euvp-dataset)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)![Synthetic](https://img.shields.io/badge/-Synthetic-purple)|RAL| There are over 12K paired and 8K unpaired instances in EUVP. Training a CycleGAN on unpaired data to learn the domain transformation between the good and poor quality images. Then the good quality images are distorted by CycleGAN to generate paired images.
2020|[OceanDark](https://sites.google.com/view/oceandark/home)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)![DeepSea](https://img.shields.io/badge/-DeepSea-brown)|CVPRW| It is composed by 183 underwater images of 1280 x 720 pixels captured by video cameras located in **profound depths** using artificial lighting.
2022|[LNRUD](https://github.com/Ephemeral182/UWNR)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)![Synthetic](https://img.shields.io/badge/-Synthetic-purple)|CVPRW| It contains 50000 clean images and 50000 corresponding underwater images synthesized from 5000 real underwater scene images and UWNR (Underwater Neural Rendering).
2023|[LSUI](https://lintaopeng.github.io/_pages/UIE%20Project%20Page.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)|TIP| A large-scale underwater image dataset including 4279 pairs of raw underwater images and corresponding high-quality reference images.
2023|[UVE-38K](https://github.com/TrentQiQ/UVE-38K)|![Video](https://img.shields.io/badge/-Video-red)![Paired](https://img.shields.io/badge/-Paired-blue)| MTA | The UVE-38K is a large real-world underwater video enhancement dataset with inter-frame consistent refference. It contains 50 video sequences with more than 38,000 frames. They adopt 12 enhancement methods to generate the enhancement candidate pool for each frame and invited volunteers to pick out the best enhancement approach for each video according to their overall performance on the whole video. The videos whose intermediate references include obvious style difference will be applied for further post-refinement to get more consistent and better reference.
2023|[DRUVA](https://github.com/nishavarghese15/DRUVA)|![Video](https://img.shields.io/badge/-Video-red)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)|ICCV| It contains 20 videos of 20 different artifacts (artifacts are mainly submerged rocks of dimension 0.5 meter to 1 meter) in shallow waters. The videos are approximately 1 minute long and contain an almost 360◦ azimuthal view of the artifacts at a depth of 0.5 meter to 4 meters from the camera.
2023|[NUID](https://github.com/Hou-Guojia/ICSP)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)![DeepSea](https://img.shields.io/badge/-DeepSea-brown)|TCSVT| It contains 925 real underwater images of different non-uniform illumination.
2024|[SUVE](https://github.com/ddz16/UVENet)| ![Video](https://img.shields.io/badge/-Video-red)![Paired](https://img.shields.io/badge/-Paired-blue)![Synthetic](https://img.shields.io/badge/-Synthetic-purple) |Arxiv| It comprises 660 pairs of training videos and 180 pairs of testing videos, covering a wide range of underwater imaging conditions. Each video contains an average of around 170 frames, resulting in over 140,000 underwater images in the entire dataset.
2024|[UVEB](https://github.com/yzbouc/UVEB)| ![Video](https://img.shields.io/badge/-Video-red)![Paired](https://img.shields.io/badge/-Paired-blue) |CVPR| It contains 1,308 pairs of video sequences and more than 453,000 high-resolution with 38% Ultra-High-Definition (UHD) 4K frame pairs. UVEB comes from multiple countries, containing various scenes and video degradation types to adapt to diverse and complex underwater environments.

## Object Detection.
Year|Dataset|Tag|Pub|Description
-----|----|-----|-----|-----
2015|[FishCLEF-2015](http://www.perceivelab.com/datasets)|![Video](https://img.shields.io/badge/-Video-red)|None| It includes 93 videos, manually-annotated with fish locations (as bounding boxes) and species. In total the dataset contains more than 14,000 annotations and 15 classes of fish.
2019|[RUIE](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark)|![Image](https://img.shields.io/badge/-Image-brightgreen)|TCSVT| It contains a subset dataset, UHTS, which contains 300 images embodying three classes of sea life, i.e., **scallop**, **sea cucumbers** and **sea urchins**.
2019|[Brackish](https://tianchi.aliyun.com/dataset/93749)|![Video](https://img.shields.io/badge/-Video-red)|CVPRW| 89 videos are provided with annotations in the AAU Bounding Box, YOLO Darknet, and MS COCO formats. Fish are annotated in 6 different coarse categories, i.e., **fish**, **small_fish**, **crab**, **shrimp**, **jellyfish**, and **starfish**.
2019|[Trash-ICRA19](https://conservancy.umn.edu/handle/11299/214366)|![Image](https://img.shields.io/badge/-Image-brightgreen)|ICRA| Some videos were processed to extract 5,700 images, which comprise this dataset, all labeled with bounding boxes on instances of **trash**, **biological objects** such as plants and animals, and **ROVs**.
2021|[DUO](https://github.com/chongweiliu/DUO)|![Image](https://img.shields.io/badge/-Image-brightgreen)|ICME| It contains 7782 images, where 6671 for training and 1111 for testing. All the images come from historical [URPC](https://openi.pcl.ac.cn/OpenOrcinus_orca) datasets and UDD dataset, i.e., **echinus**, **holothurian**, **starfish** and **scallop**.
2023|[FishNet](https://fishnet-2023.github.io/)|![Image](https://img.shields.io/badge/-Image-brightgreen)|ICCV| It contains 94,532 meticulously organized images from 17,357 aquatic species, organized according to aquatic biological taxonomy (order, family, genus, and species). All instances in each image are labelled bounding boxes, resulting in 114,375 object instances.


## Object Tracking.
Year|Dataset|Tag|Pub|Description
-----|----|-----|-----|-----
2021|[UOT100](https://www.kaggle.com/datasets/landrykezebou/uot100-underwater-object-tracking-dataset/data)|![Video](https://img.shields.io/badge/-Video-red)|IJOE| It consists of 104 video sequences and over 74 000 annotated frames.


## Semantic Segmentation.
Year|Dataset|Tag|Pub|Description
-----|----|-----|-----|-----
2020|[SUIM](https://irvlab.cs.umn.edu/resources/suim-dataset)|![Image](https://img.shields.io/badge/-Image-brightgreen)|IROS| It contains over 1500 images with pixel annotations for eight object categories: **fish (vertebrates)**, **reefs (invertebrates)**, **aquatic plants**, **wrecks/ruins**, **human divers**, **robots**, and **sea-floor**.
2020|[TrashCan](https://conservancy.umn.edu/handle/11299/214865)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Instance](https://img.shields.io/badge/-Instance-yellow)|None| It contains 7212 images and four big classes: **trash**(any marine debris), **ROV**(any man-made item), **bio**(plants and animals) and **unknown**(unknown objects). Trash objects were additionally tagged by material (e.g., metal, plastic), instance (e.g., cup, bag), along with binary tags indicating overgrowth, significant decay, or crushed/broken items. Bio objects are plants or animals, and in the case of animals, having six classes (**crab**, **fish**, **eel**, **shells**, **starfish**, **etc**). ROV and unknown objects have no additional tags.
2023|[UIIS](https://github.com/LiamLian0727/WaterMask)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Instance](https://img.shields.io/badge/-Instance-yellow)|ICCV| It contains 4,628 images for 7 categories with pixel-level annotations for underwater instance segmentation task: **Fish**(Fish and other vertebrates), **Reefs**(Coral reefs and other invertebrates), **Aquatic plants**( Aquatic plants and flora), **Wrecks/ruins**( Underwater damaged man-made artifacts), **Human divers**( Human and the diving equipment they carry), **Robots**( AUV, ROV and other underwater robots), and **Sea-floor**(Sea-floor Rocks and reefs on the seafloor).


## Classification.
Year|Dataset|Tag|Pub|Description
-----|----|-----|-----|-----
2012|[Fish4Knowledge](https://homepages.inf.ed.ac.uk/rbf/Fish4Knowledge/GROUNDTRUTH/RECOG/)|![Image](https://img.shields.io/badge/-Image-brightgreen)|ICPR| It consists of 27370 verified fish images. The whole dataset is divided into 23 clusters and each cluster is presented by a representative species, which is based on the synapomorphies characteristic from the extent that the taxon is monophyletic.
2015|[FishCLEF-2015](http://www.perceivelab.com/datasets)|![Video](https://img.shields.io/badge/-Video-red)|None| It consists of 20,000 sample images and 15 fish categories.
2018|[WildFish](https://github.com/PeiqinZhuang/WildFish)|![Image](https://img.shields.io/badge/-Image-brightgreen)|ACMMM| It consists of 1000 fish categories with 54,459 unconstrained images.
2023|[FishNet](https://fishnet-2023.github.io/)|![Image](https://img.shields.io/badge/-Image-brightgreen)|ICCV| It contains 94,532 meticulously organized images from 17,357 aquatic species, organized according to aquatic biological taxonomy (order, family, genus, and species).
