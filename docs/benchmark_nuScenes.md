## nuScenes Benchmarks

We present the nuScenes *validation* and *testing* benchmarks in this page (we ignore the methods without any publications or technical reports), and the offical benchmark can found in [[here]](https://www.nuscenes.org/object-detection?externalData=all&mapData=all&modalities=Camera). Becuase only few works apply auxiliary data in this dataset, we merge all methods in the same benchmark, and indicate the methods with other data or designs which may lead to unfair comparison. (D: DDAD15M Pre-Training, T: Test-Time Augmentation, M: Model Ensemble)



#### Testing Set

|      | note | mAP | mATE | mASE | mAOE | mAVE | mAAE | NDS\* |
| ---- | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf) | D | 0.424 | 0.524 | 0.242 | 0.373 | 0.950 | 0.148 | 0.488 |
| [DETR3D](https://arxiv.org/pdf/2110.06922.pdf) | D | 0.412 | 0.641 | 0.255 | 0.394 | 0.845 | 0.133 | 0.479 |
| [DD3D](https://arxiv.org/pdf/2108.06417.pdf) | D | 0.418 | 0.572 | 0.249 | 0.368 | 1.014 | 0.124 | 0.477 |
| [BEVDet-pure](https://arxiv.org/pdf/2112.11790.pdf) | - | 0.398 | 0.556 | 0.239 | 0.414 | 1.010 | 0.153 | 0.463 |
| [PGD](https://arxiv.org/pdf/2107.14160.pdf) | - | 0.386 | 0.626 | 0.245 | 0.451 | 1.509 | 0.127 | 0.448 |
| [FCOS3D](https://arxiv.org/pdf/2104.10956.pdf) | T, M | 0.358 | 0.690 | 0.249 | 0.452 | 1.434 | 0.124 | 0.428 |
| [CenterNet](https://arxiv.org/pdf/1904.07850.pdf) | - | 0.338 | 0.658 | 0.255 | 0.629 | 1.629 | 0.142 | 0.400 
| [Time3D](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Time3D_End-to-End_Joint_Monocular_3D_Object_Detection_and_Tracking_for_CVPR_2022_paper.pdf) | - | 0.312 | 0.732 | 0.254 | 0.504 | 1.523 | 0.121 | 0.394 |

| [MonoDIS](https://arxiv.org/pdf/1905.12365.pdf) | - | 0.304 | 0.738 | 0.263 | 0.546 | 1.553 | 0.134 | 0.384 |




#### Validation Set


|      | note | mAP | mATE | mASE | mAOE | mAVE | mAAE | NDS\* |
| ---- | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| [DETR3D](https://arxiv.org/pdf/2110.06922.pdf) | - | 0.349 | 0.716 | 0.268 | 0.379 | 0.842 | 0.200 | 0.434 |
| [PGD](https://arxiv.org/pdf/2107.14160.pdf) | - | 0.369 | 0.683 | 0.260 | 0.439 | 1.268 | 0.185 | 0.428 |
| [BEVDet](https://arxiv.org/pdf/2112.11790.pdf) | - | 0.349 | 0.637 | 0.269 | 0.490 | 0.914 | 0.268 | 0.417 |
| [FCOS3D](https://arxiv.org/pdf/2104.10956.pdf) | T, M | 0.343 | 0.725 | 0.263 | 0.422 | 1.292 | 0.153 | 0.415 |
| [CenterNet](https://arxiv.org/pdf/1904.07850.pdf) | - | 0.306 | 0.716 | 0.264 | 0.609 | 1.426 | 0.658 | 0.328 |

