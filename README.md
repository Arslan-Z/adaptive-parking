## Adaptive Parking Slot Occupancy Detection Using Vision Transformer and LLIE
-----------------
<div align="center">
  <img src="assets/carpark.png"><br><br>
</div>


[![Join the chat at https://gitter.im/adaptive-parking/community](https://badges.gitter.im/adaptive-parking/users.svg)](https://gitter.im/adaptive-parking/community) [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://raw.githubusercontent.com/karthickai/adaptive-parking/master/LICENSE)


## Dataset

Please keep in mind that this dataset is exclusively available for academic research. The copyright to some photos is owned by the original proprietors of the [PKLot](https://web.inf.ufpr.br/vri/databases/parking-lot-database/) and [CARPK](https://lafi.github.io/LPN/) datasets. If you own any of the photographs and would like them removed, please let us know, and we will do so.


Using PKLot and CARPK, we constructed a tailored dataset. We randomly chosen 1,257 photos from PKLot and CARPK, and 20 percent of them were converted to a low-light image by lowering the exposure value. Aerial and standard view vehicle images are included in this dataset. The primary goal of this dataset is to create a standard benchmark dataset for aerial/standard vehicle slot occupancy detection even in low light conditions.

|    Type       | Total Images| Size in mb   |
| ------------- | ----------- | ------------ |
| Aerial        | 484         | 650          |
| Standard      | 773         | 96.2         |
| Total         | 1257        | 746.2        |    

We annotated the dataset in the COCO JSON format, dataset.json available in the Dataset folder of root directory. It is nearly 20Mb in size. 

## Legal Notice

Adaptive Parking Slot Ocuupacny Detection Dataset is made available under the MIT license found in the ``LICENSE`` file. An MIT license is one of several public copyright licenses that enable the free distribution of otherwise copyrighted work.

The dataset consists of 1257 still images with more than 10000 marked polygons of parking blocks in COCO JSON format. The images were extracted from CARPK and PKLot Dataset. Therefore, users are entitled to use this image under these conditions:

1. Comply with the license file on the ``LICENSE`` file.
2. Comply with best practices for attribution found here: https://wiki.creativecommons.org/wiki/best_practices_for_attribution.
3. Understand that the authors make no guarantee or warranty of non-infringement concerning the dataset.

## How to Cite

Kindly cite this dataset using the following ``bibtex`` reference:

```
@INPROCEEDINGS{Pann2109:Adaptive,
AUTHOR="Karthick Pannerselvam",
TITLE="Adaptive Parking Slot Occupancy Detection Using Vision Transformer and
{LLIE}",
BOOKTITLE="2021 IEEE International Smart Cities Conference (ISC2) (IEEE ISC2 2021)",
ADDRESS=virtual,
DAYS=7,
MONTH=sep,
YEAR=2021,
}
```
