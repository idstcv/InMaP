# InMaP
PyTorch Implementation for Our NeurIPS'23 Paper: "Intra-Modal Proxy Learning for Zero-Shot Visual Categorization with CLIP"

## Requirements
* Python 3.9
* PyTorch 1.12
* [CLIP](https://github.com/openai/CLIP)

## Usage:
InMaP with pre-trained ResNet-50
```
python main.py -a RN50 --data_path /path/to/imagenet
```

## Citation
If you use the package in your research, please cite our paper:
```
@inproceedings{qian2023inmap,
  author    = {Qi Qian and
               Yuanhong Xu and
               Juhua Hu},
  title     = {Intra-Modal Proxy Learning for Zero-Shot Visual Categorization with CLIP},
  booktitle = {Thirty-seventh Conference on Neural Information Processing Systems, {NeurIPS} 2023},
  year      = {2023}
}
```