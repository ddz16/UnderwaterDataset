# UnderwaterDataset
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
![Stars](https://img.shields.io/github/stars/ddz16/UnderwaterDataset)

This repository contains various underwatr datasets for enhancement, detection, segmentation...

Each dataset contains the following types of data:
![Image](https://img.shields.io/badge/-Image-brightgreen)
![Video](https://img.shields.io/badge/-Video-red)
![Paired](https://img.shields.io/badge/-Paired-blue)
![RawOnly](https://img.shields.io/badge/-RawOnly-pink)
![Depth](https://img.shields.io/badge/-Depth-orange)
![Synthetic](https://img.shields.io/badge/-Synthetic-purple)


## Enhancement/Restoration.
Year|Dataset|Type|Pub|Description
-----|----|---|-----|-----
2019|[SQUID](https://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)![Depth](https://img.shields.io/badge/-Depth-orange)|TPAMI| It includes RAW images, TIF files, camera clibration files, and distance maps. The database contains 57 stereo pairs from four different sites.
2019|[U45](https://github.com/IPNUISTlegal/underwater-test-dataset-U45-)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)|None| A pubic underwater test dataset including 45 images suffering from the color casts, low contrast and haze-like effects of underwater degradation.
2019|[Sea-thru](https://csms.haifa.ac.il/profiles/tTreibitz/datasets/sea_thru/index.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)![Depth](https://img.shields.io/badge/-Depth-orange)|CVPR| It includes RAW images (.ARW or .DEF files) and corresponding depth maps (.tif files).
2019|[RUIE](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)|TCSVT| It contains two subset datasets, UIQS and UCCS, which contain only raw underwater images to test UIE algorithms for the ability of improving visibility and correcting color casts, respectively.
2019|[UIEB](https://li-chongyi.github.io/proj_benchmark.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)|TIP| UIEB includes two subsets: 890 raw underwater images with corresponding high-quality reference images; 60 challenging underwater images.
2020|[EUVP](https://irvlab.cs.umn.edu/resources/euvp-dataset)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)![Synthetic](https://img.shields.io/badge/-Synthetic-purple)|RAL| There are over 12K paired and 8K unpaired instances in EUVP. Training a CycleGAN on unpaired data to learn the domain transformation between the good and poor quality images. Then the good quality images are distorted by CycleGAN to generate paired images.
2020|[OceanDark](https://sites.google.com/view/oceandark/home)|![Image](https://img.shields.io/badge/-Image-brightgreen)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)|CVPRW| It is composed by 183 underwater images of 1280 x 720 pixels captured by video cameras located in **profound depths** using artificial lighting.
2022|[LNRUD](https://github.com/Ephemeral182/UWNR)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)![Synthetic](https://img.shields.io/badge/-Synthetic-purple)|CVPRW| It contains 50000 clean images and 50000 corresponding underwater images synthesized from 5000 real underwater scene images and UWNR (Underwater Neural Rendering).
2023|[LSUI](https://lintaopeng.github.io/_pages/UIE%20Project%20Page.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)![Paired](https://img.shields.io/badge/-Paired-blue)|TIP| A large-scale underwater image dataset including 4279 pairs of raw underwater images and corresponding high-quality reference images.
2023|[DRUVA](https://github.com/nishavarghese15/DRUVA)|![Video](https://img.shields.io/badge/-Video-red)![RawOnly](https://img.shields.io/badge/-RawOnly-pink)|ICCV| It contains 20 videos of 20 different artifacts (artifacts are mainly submerged rocks of dimension 0.5 meter to 1 meter) in shallow waters. The videos are approximately 1 minute long and contain an almost 360◦ azimuthal view of the artifacts at a depth of 0.5 meter to 4 meters from the camera.


## Object Detection.
Year|Dataset|Tag|Pub|Description
-----|----|-----|-----|-----
2019|[RUIE](https://github.com/dlut-dimt/Realworld-Underwater-Image-Enhancement-RUIE-Benchmark)|![Image](https://img.shields.io/badge/-Image-brightgreen)|TCSVT| It contains a subset dataset, UHTS, which contains 300 images embodying three classes of sea life, i.e., **scallop**, **sea cucumbers** and **sea urchins**.
2021|[DUO](https://github.com/chongweiliu/DUO)|![Image](https://img.shields.io/badge/-Image-brightgreen)|ICME| It contains 7782 images, where 6671 for training and 1111 for testing. all the images come from historical URPC datasets and UDD dataset, i.e., **echinus**, **holothurian**, **starfish** and **scallop**.

## Semantic Segmentation.
Year|Dataset|Tag|Pub|Description
-----|----|-----|-----|-----
2020|[SUIM](https://irvlab.cs.umn.edu/resources/suim-dataset)|![Image](https://img.shields.io/badge/-Image-brightgreen)|IROS| It contains over 1500 images with pixel annotations for eight object categories: **fish (vertebrates)**, **reefs (invertebrates)**, **aquatic plants**, **wrecks/ruins**, **human divers**, **robots**, and **sea-floor**.
