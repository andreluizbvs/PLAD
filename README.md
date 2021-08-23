# PLAD: A Dataset for Multi-Size Power Line Assets Detection in High-Resolution UAV Images

This repo stores the Power Line Assets Dataset from the paper: PLAD: A Dataset for Multi-Size Power Line Assets Detection in High-Resolution UAV Images.

[Dataset](https://drive.google.com/file/d/1KsNziErZ5ZRuWBpwUS5nlTnb8CcB2uQp/view?usp=sharing) (Google Drive)

This paper has been accepted for presentation at SIBGRAPI 2021 [(arXiv)](https://arxiv.org/abs/2108.07944).

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/plad-a-dataset-for-multi-size-power-line/object-detection-on-plad)](https://paperswithcode.com/sota/object-detection-on-plad?p=plad-a-dataset-for-multi-size-power-line)

## Properties
- Image size: 5472×3078 or 5472×3648
- Total images: 133
- Total instances: 2409
- Average instances per image: 18.1
- Nº of object classes (different assets): 5
- Other stats:

![Properties](https://i.imgur.com/HzdL7bF.png)

## Baseline results

- mAP: 89.2%

| Assets             | Average Precision |
|--------------------|:-----------------:|
| Transmission tower |       0.900       |
| Insulator          |       0.894       |
| Spacer             |       0.856       |
| Tower plate        |       0.971       |
| Stockbridge damper |       0.838       |
| **mean**           |     **0.892**     |

## Sample images
![Images](https://i.imgur.com/xIe5jbr.png)

## Sample assets
![Assets](https://i.imgur.com/7j6qe11.png)

## Abstract

Many power line companies are using UAVs to perform their inspection processes instead of putting their workers at risk by making them climb high voltage power line towers, for instance. A crucial task for the inspection is to detect and classify assets in the power transmission lines. However, public data related to power line assets are scarce, preventing a faster evolution of this area. This work proposes the Power Line Assets Dataset, containing high-resolution and real-world images of multiple high-voltage power line components. It has 2,409 annotated objects divided into five classes: transmission tower, insulator, spacer, tower plate, and Stockbridge damper, which vary in size (resolution), orientation, illumination, angulation, and background. This work also presents an evaluation with popular deep object detection methods, showing considerable room for improvement.

## Citing

```
@misc{vieiraesilva2021plad,
      title={PLAD: A Dataset for Multi-Size Power Line Assets Detection in High-Resolution UAV Images}, 
      author={André Luiz Buarque Vieira-e-Silva and Heitor de Castro Felix and Thiago de Menezes Chaves and Francisco Paulo Magalhães Simões and Veronica Teichrieb and Michel Mozinho dos Santos and Hemir da Cunha Santiago and Virginia Adélia Cordeiro Sgotti and Henrique Baptista Duffles Teixeira Lott Neto},
      year={2021},
      eprint={2108.07944},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

## Authors

- André Luiz Buarque Vieira-e-Silva (albvs@cin.ufpe.br)
- Voxar Labs (voxarlabs@cin.ufpe.br) - https://www.cin.ufpe.br/~voxarlabs/


