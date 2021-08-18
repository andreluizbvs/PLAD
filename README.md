# PLAD: A Dataset for Multi-Size Power Line Assets Detection in High-Resolution UAV Images

This repo stores the Power Line Assets Dataset from the paper: PLAD: A Dataset for Multi-Size Power Line Assets Detection in High-Resolution UAV Images.

[Dataset](https://drive.google.com/file/d/1KsNziErZ5ZRuWBpwUS5nlTnb8CcB2uQp/view?usp=sharing) (Google Drive)

This paper has been accepted for presentation at SIBGRAPI 2021. [arXiv](https://drive.google.com/file/d/1v4B1C2KpIjNywjhSI3p-5WIrB29S9q9M/view?usp=sharing)


## Properties
- Image size: 5472×3078 or 5472×3648
- Total images: 133
- Total instances: 2409
- Average instances per image: 18.1
- Nº of object classes (different assets): 5
- Other stats:

![Properties](https://i.imgur.com/txWWPGN.png)

## Baseline results

- mAP: 89.2%

| Assets             | Average Precision |
|--------------------|-------------------|
| Transmission tower | 0.900             |
| Insulator          | 0.894             |
| Spacer             | 0.856             |
| Tower plate        | 0.971             |
| Stockbridge damper | 0.838             |
| **mean**           | **0.892**         |

## Sample images
![Images](https://i.imgur.com/xIe5jbr.png)

## Sample assets
![Assets](https://i.imgur.com/7j6qe11.png)

## Abstract

Many power line companies are using UAVs to perform their inspection processes instead of putting their workers at risk by making them climb high voltage power line towers, for instance. A crucial task for the inspection is to detect and classify assets in the power transmission lines. However, public data related to power line assets are scarce, preventing a faster evolution of this area. This work proposes the Power Line Assets Dataset, containing high-resolution and real-world images of multiple high-voltage power line components. It has 2,409 annotated objects divided into five classes: transmission tower, insulator, spacer, tower plate, and Stockbridge damper, which vary in size (resolution), orientation, illumination, angulation, and background. This work also presents an evaluation with popular deep object detection methods, showing considerable room for improvement.

## Authors

- André Luiz Buarque Vieira-e-Silva (albvs@cin.ufpe.br)
- Voxar Labs (voxarlabs@cin.ufpe.br) - https://www.cin.ufpe.br/~voxarlabs/


