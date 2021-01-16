# Awesome Transformer in Vision [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)  
A curated list of vision transformer related resources. Please feel free to [pull requests](https://github.com/penghouwen/VisionTransformer/pulls) or [open an issue](https://github.com/penghouwen/VisionTransformer/issues) to add papers.


## Table of Contents

- [Awesome Surveys](#awesome-surveys)

- [Transformer in Vision](#transformer-in-vision)
  - [2021 Venues](#2021)
  - [2020 Venues](#2020)
  - [2019 Venues](#2019)
  - [Previous Venues](#2012-2018)
  
  - [Awesome Libraies](#awesome-surveys)

## Awesome Surveys

|  Title  |   Venue  |   BibTeX  |
|:--------|:--------:|:--------:|
| [A Survey on Visual Transformer](https://arxiv.org/pdf/2012.12556.pdf) | ArXiv | [Bib](https://scholar.googleusercontent.com/scholar.bib?q=info:Aj10Crv7DScJ:scholar.google.com/&output=citation&scisdr=CgUmooQTEM3KnAOogfQ:AAGBfm0AAAAAX_-tmfT1yhaAeO62lS61HGcSpcXSUqJ5&scisig=AAGBfm0AAAAAX_-tmQAIcm-VKBRqnb9iTs8Sghq-6ssB&scisf=4&ct=citation&cd=-1&hl=ja)

## Transformer in Vision

|      Task   |        Reg       |       Det    |           Seg           |        Trk           |    Other   |
|:------------|:--------------:|:----------------------:|:-----------------------:|:----------------------:|:----------:|
| Explanation | Image Recoginition | Object Detection | Image Segmentation | Object Tracking | other types |

You can add a tag for `domains` which contains several transformer-based works

### 2021
(Pls follow Time Inverse Ranking)

|  Title  |   Venue  |  Task  |   Code   |  BibTeX  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [TrackFormer: Multi-Object Tracking with Transformers](https://arxiv.org/abs/2101.02702) | Arxiv | Trk | [GitHub]() | [Bib](https://scholar.googleusercontent.com/scholar.bib?q=info:FPvKVRbtrIsJ:scholar.google.com/&output=citation&scisdr=CgUmooVjENWd0wS0GSo:AAGBfm0AAAAAX_-xASqzkmKVlI_ghtAFBTJPBLDUYfFD&scisig=AAGBfm0AAAAAX_-xAQWgW5KYRtnhpPb41ke6jWK4XpsF&scisf=4&ct=citation&cd=-1&hl=zh-CN)


### 2020

|  Title  |   Venue  |  Task  |   Code   |  BibTeX  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [Training data-efficient image transformers & distillation through attention](https://arxiv.org/abs/2012.12877) | ArXiv | Reg | [GitHub](https://github.com/facebookresearch/deit) | <details> <summary>Bib</summary> <p align="left">   </br> @article{touvron2020training, </br> title={Training data-efficient image transformers \& distillation through attention}, </br> author={Touvron, Hugo and Cord, Matthieu and Douze, Matthijs and Massa, Francisco and Sablayrolles, Alexandre and J{\'e}gou, Herv{\'e}}, </br> journal={arXiv preprint arXiv:2012.12877}, </br> year={2020} </br> } </br> </p></details> </br>
| [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929) | ICLR | Reg | [GitHub](https://github.com/google-research/vision_transformer) | <details> <summary>Bib</summary> <p align="left">   </br> @article{dosovitskiy2020image, </br> title={An image is worth 16x16 words: Transformers for image recognition at scale}, </br> author={Dosovitskiy, Alexey and Beyer, Lucas and Kolesnikov, Alexander and Weissenborn, Dirk and Zhai, Xiaohua and Unterthiner, Thomas and Dehghani, Mostafa and Minderer, Matthias and Heigold, Georg and Gelly, Sylvain and others}, </br> journal={arXiv preprint arXiv:2010.11929}, </br> year={2020} </br> } </p></details> </br>
| [ Toward Transformer-Based Object Detection](https://arxiv.org/abs/2012.09958) | ArXiv | Det | --- | <details> <summary>Bib</summary> <p align="left"> </br> @article{beal2020toward, </br> title={Toward Transformer-Based Object Detection}, </br> author={Beal, Josh and Kim, Eric and Tzeng, Eric and Park, Dong Huk and Zhai, Andrew and Kislyuk, Dmitry}, </br> journal={arXiv preprint arXiv:2012.09958}, </br> year={2020} </br> } </p></details> </br>
| [ Rethinking Transformer-based Set Prediction for Object Detection](https://arxiv.org/abs/2011.10881) | ArXiv | Det | --- | <details> <summary>Bib</summary> <p align="left">   </br> @article{sun2020rethinking, </br> title={Rethinking Transformer-based Set Prediction for Object Detection}, </br> author={Sun, Zhiqing and Cao, Shengcao and Yang, Yiming and Kitani, Kris}, </br> journal={arXiv preprint arXiv:2011.10881}, </br> year={2020} </br> } </p></details> </br>
| [ UP-DETR: Unsupervised Pre-training for Object Detection with Transformers](https://arxiv.org/abs/2011.09094) | ArXiv | Det | --- | <details> <summary>Bib</summary> <p align="left">   </br> @article{dai2020up, </br> title={UP-DETR: Unsupervised Pre-training for Object Detection with Transformers}, </br> author={Dai, Zhigang and Cai, Bolun and Lin, Yugeng and Chen, Junying}, </br> journal={arXiv preprint arXiv:2011.09094}, </br> year={2020} </br> } </p></details> </br>
| [ Deformable DETR: Deformable Transformers for End-to-End Object Detection](https://arxiv.org/abs/2010.04159) | ArXiv | Det | [ GitHub]( https://github.com/fundamentalvision/Deformable-DETR) | <details> <summary>Bib</summary> <p align="left">   </br> @article{zhu2020deformable, </br> title={Deformable DETR: Deformable Transformers for End-to-End Object Detection}, </br> author={Zhu, Xizhou and Su, Weijie and Lu, Lewei and Li, Bin and Wang, Xiaogang and Dai, Jifeng}, </br> journal={arXiv preprint arXiv:2010.04159}, </br> year={2020} </br> } </p></details> </br>
| [ End-to-End Object Detection with Transformers](https://arxiv.org/abs/2005.12872) | ECCV | Det | [ GitHub]( https://github.com/facebookresearch/detr) | <details> <summary>Bib</summary> <p align="left">  article{zhu2020deformable, </br>  title={Deformable DETR: Deformable Transformers for End-to-End Object Detection}, </br>  author={Zhu, Xizhou and Su, Weijie and Lu, Lewei and Li, Bin and Wang, Xiaogang and Dai, Jifeng}, </br>  journal={arXiv preprint arXiv:2010.04159}, </br>   year={2020} </br> } </br> </p></details>  
| [ MaX-DeepLab: End-to-End Panoptic Segmentation with Mask Transformers](https://arxiv.org/abs/2012.00759) | --- | Seg | [ ---]( ---) | <details> <summary>Bib</summary> <p align="left">  @article{wang2020max, </br>  title={MaX-DeepLab: End-to-End Panoptic Segmentation with Mask Transformers}, </br>   author={Wang, Huiyu and Zhu, Yukun and Adam, Hartwig and Yuille, Alan and Chen, Liang-Chieh}, </br>   journal={arXiv preprint arXiv:2012.00759}, </br>   year={2020} </br> }  </br> </p></details>  
| [ ---](https://arxiv.org/abs/2010.11929) | --- | Seg | [ ---]( ---) | [Bib]( ---)
| [TransTrack: Multiple-Object Tracking with Transformer](https://arxiv.org/abs/2012.15460) | ArXiv | Trk | [GitHub](https://github.com/PeizeSun/TransTrack) | <details> <summary>Bib</summary> <p align="left">   </br> @article{sun2020transtrack, </br> title={TransTrack: Multiple-Object Tracking with Transformer}, </br> author={Sun, Peize and Jiang, Yi and Zhang, Rufeng and Xie, Enze and Cao, Jinkun and Hu, Xinting and Kong, Tao and Yuan, Zehuan and Wang, Changhu and Luo, Ping}, </br> journal={arXiv preprint arXiv:2012.15460}, </br> year={2020} </br> } </p></details> </br>


### 2019

|  Title  |   Venue  |  Task  |   Code   |  BibTeX  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [Training data-efficient image transformers & distillation through attention](https://arxiv.org/abs/2012.12877) | ArXiv | Reg | [GitHub](https://github.com/facebookresearch/deit) | -
| [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929) | ICLR | Reg | [GitHub](https://github.com/google-research/vision_transformer) | -

### 2012-2018

|  Title  |   Venue  |  Task  |   Code   |  BibTeX  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [Attention Is All You Need](https://papers.nips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) | NeurIPS'17 | -- | [GitHub](https://github.com/tensorflow/tensor2tensor) | <details> <summary>Bib</summary> <p align="left">  @inproceedings{vaswani2017attention, </br>   title={Attention is all you need}, </br>   author={Vaswani, Ashish and Shazeer, Noam and Parmar, Niki and Uszkoreit, Jakob and Jones, Llion and Gomez, Aidan N and Kaiser, {\L}ukasz and Polosukhin, Illia}, </br>  booktitle={Advances in neural information processing systems}, </br>  pages={5998--6008}, </br>   year={2017} </br> }  </p></details>

## Awesome vTransformer Libraies
- [WaitingToAdd](https://github.com/penghouwen/VisionTransformer/blob/main/README.md)

