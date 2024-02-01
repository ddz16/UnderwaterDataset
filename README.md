# UnderwaterDataset
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
![Stars](https://img.shields.io/github/stars/ddz16/UnderwaterDataset)

This repository contains various underwatr datasets for enhancement, detection, segmentation...

Each dataset contains the following types of data:
![Image](https://img.shields.io/badge/-Image-brightgreen)
![Video](https://img.shields.io/badge/-Video-red)


## Underwater Image Enhancement/Restoration.
Year|Dataset|Type|Pub|Description
-----|----|-----|-----|-----
2019|[U45](https://github.com/IPNUISTlegal/underwater-test-dataset-U45-)|![Image](https://img.shields.io/badge/-Image-brightgreen)|None| A pubic underwater test dataset including 45 images suffering from the color casts, low contrast and haze-like effects of underwater degradation.
2019|[UIEB](https://li-chongyi.github.io/proj_benchmark.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)|TIP| UIEB includes two subsets: 890 raw underwater images with corresponding high-quality reference images; 60 challenging underwater images.
2020|[EUVP](https://irvlab.cs.umn.edu/resources/euvp-dataset)|![Image](https://img.shields.io/badge/-Image-brightgreen)|RAL| There are over 12K paired and 8K unpaired instances in EUVP. Training a CycleGAN on unpaired data to learn the domain transformation between the good and poor quality images. Then the good quality images are distorted by CycleGAN to generate paired images.
2023|[LSUI](https://lintaopeng.github.io/_pages/UIE%20Project%20Page.html)|![Image](https://img.shields.io/badge/-Image-brightgreen)|TIP| A large-scale underwater image dataset including 4279 pairs of raw underwater images and corresponding high-quality reference images.


## Semantic Segmentation.
Year|Dataset|Tag|Pub|Description
-----|----|-----|-----|-----
2020|[SUIM](https://irvlab.cs.umn.edu/resources/suim-dataset)|![Image](https://img.shields.io/badge/-Image-brightgreen)|IROS| It contains over 1500 images with pixel annotations for eight object categories: fish (vertebrates), reefs (invertebrates), aquatic plants, wrecks/ruins, human divers, robots, and sea-floor.
