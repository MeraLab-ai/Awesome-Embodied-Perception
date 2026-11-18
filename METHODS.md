# Methods for embodied perception

[Overview](README.md) · [References](REFERENCES.md) · [All method-chapter papers](CHAPTERS.md#sec-3)

The tables cover 100 method papers across 11 categories: 93 from Figure 2 and seven additional papers discussed in the text. ConceptGraphs appears under region-level, object-level temporal, and object–scene temporal fusion. MVX-Net appears under both point-level and voxel-level fusion for its two variants. The two entries named Hydra refer to different papers.

- [Point-level Fusion](#sec-3-1)
- [Voxel-level Fusion](#sec-3-2)
- [Region-level Fusion](#sec-3-3)
- [Multi-level Fusion](#sec-3-4)
- [Object-Level Temporal Fusion](#sec-4-1)
- [Scene-Level Temporal Fusion](#sec-4-2)
- [Object–Scene Temporal Fusion](#sec-4-3)
- [Collaborative Fusion](#sec-5-1)
- [Agent-to-Agent Communication](#sec-5-2)
- [Vision–Language Models](#sec-6-1)
- [LLMs with Other Sensor Modalities](#sec-6-2)

<a name="sec-3-1"></a>

## Point-level Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **Frustum PointNets** | Frustum pointnets for 3d object detection from rgb-d data | CVPR · 2018 | [Paper](https://doi.org/10.1109/cvpr.2018.00102) · [Code](https://github.com/charlesq34/frustum-pointnets) | [18](REFERENCES.md#ref-018) |
| **PointFusion** | Pointfusion: Deep sensor fusion for 3d bounding box estimation | CVPR · 2018 | [Paper](https://openaccess.thecvf.com/content_cvpr_2018/html/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.html) | [19](REFERENCES.md#ref-019) |
| **PI-RCNN** | PI-RCNN: An efficient multi-sensor 3D object detector with point-based attentive cont-conv fusion module | AAAI · 2020 | [Paper](https://doi.org/10.1609/aaai.v34i07.6933) · [Code](https://github.com/ZJULearning/PI-RCNN) | [20](REFERENCES.md#ref-020) |
| **PointPainting** | Pointpainting: Sequential fusion for 3d object detection | CVPR · 2020 | [Paper](https://doi.org/10.1109/cvpr42600.2020.00466) · [Project](https://motional.com/news/pointpainting-sequential-fusion-3d-object-detection) | [21](REFERENCES.md#ref-021) |
| **FusionPainting** | Fusionpainting: Multimodal fusion with adaptive attention for 3d object detection | ITSC · 2021 | [Paper](https://arxiv.org/abs/2106.12449) | [22](REFERENCES.md#ref-022) |
| **MVP** | Multimodal virtual point 3d detection | NeurIPS · 2021 | [Paper](https://papers.nips.cc/paper/2021/hash/895daa408f494ad58006c47a30f51c1f-Abstract.html) · [Code](https://github.com/tianweiy/MVP) | [23](REFERENCES.md#ref-023) |
| **PointSee** | PointSee: Image enhances point cloud | IEEE TVCG · 2023 | [Paper](https://doi.org/10.1109/TVCG.2023.3331779) | [24](REFERENCES.md#ref-024) |
| **DeepFusion** | Deepfusion: Lidar-camera deep fusion for multi-modal 3d object detection | CVPR · 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_DeepFusion_Lidar-Camera_Deep_Fusion_for_Multi-Modal_3D_Object_Detection_CVPR_2022_paper.html) · [Code](https://github.com/tensorflow/lingvo/blob/master/lingvo/tasks/car/deep_fusion.py) | [25](REFERENCES.md#ref-025) |
| **GraphAlign** | Graphalign: Enhancing accurate feature alignment by graph matching for multi-modal 3d object detection | ICCV · 2023 | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Song_GraphAlign_Enhancing_Accurate_Feature_Alignment_by_Graph_matching_for_Multi-Modal_ICCV_2023_paper.html) | [26](REFERENCES.md#ref-026) |

**Additional methods discussed in the text**

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **Li et al. (power-grid segmentation)** | A multi-sensor fusion approach combined with RandLA-Net for large-scale point cloud segmentation in power grid scenario | Sensors · 2025 | [Paper](https://doi.org/10.3390/s25113350) | [129](REFERENCES.md#ref-129) |
| **MVX-Net (PointFusion variant)** | Mvx-net: Multimodal voxelnet for 3d object detection | ICRA · 2019 | [Paper](https://arxiv.org/abs/1904.01649) | [133](REFERENCES.md#ref-133) |

<a name="sec-3-2"></a>

## Voxel-level Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **CenterFusion** | CenterFusion: Center-based Radar and Camera Fusion for 3D Object Detection | WACV · 2021 | [Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Nabati_CenterFusion_Center-Based_Radar_and_Camera_Fusion_for_3D_Object_Detection_WACV_2021_paper.pdf) · [Code](https://github.com/mrnabati/CenterFusion) | [27](REFERENCES.md#ref-027) |
| **VPFNet** | Vpfnet: Improving 3d object detection with virtual point based lidar and stereo data fusion | IEEE TMM · 2022 | [Paper](https://doi.org/10.1109/tmm.2022.3189778) · [Code](https://github.com/zhukevkesky/VPFNet) | [28](REFERENCES.md#ref-028) |
| **PointAugmenting** | Pointaugmenting: Cross-modal augmentation for 3d object detection | CVPR · 2021 | [Paper](https://doi.org/10.1109/cvpr46437.2021.01162) · [Code](https://github.com/VISION-SJTU/PointAugmenting) | [29](REFERENCES.md#ref-029) |
| **VFF** | Voxel field fusion for 3d object detection | CVPR · 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Voxel_Field_Fusion_for_3D_Object_Detection_CVPR_2022_paper.html) · [Code](https://github.com/JIA-Lab-research/VFF) | [30](REFERENCES.md#ref-030) |
| **Hydra** | Foundations of spatial perception for robotics: Hierarchical representations and real-time systems | IJRR · 2024 | [Paper](https://doi.org/10.1177/02783649241229725) · [Code](https://github.com/MIT-SPARK/Hydra) | [31](REFERENCES.md#ref-031) |
| **AutoAlign** | Autoalign: Pixel-instance feature aggregation for multi-modal 3d object detection | arXiv · 2022 | [Paper](https://arxiv.org/abs/2201.06493) | [32](REFERENCES.md#ref-032) |
| **AutoAlignV2** | Deformable feature aggregation for dynamic multi-modal 3D object detection | ECCV · 2022 | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-20074-8_36) · [Code](https://github.com/zehuichen123/AutoAlignV2) | [33](REFERENCES.md#ref-033) |
| **VoxelNeXtFusion** | Voxelnextfusion: A simple, unified and effective voxel fusion framework for multi-modal 3d object detection | arXiv · 2024 | [Paper](https://arxiv.org/abs/2401.02702) | [34](REFERENCES.md#ref-034) |
| **UVTR** | Unifying voxel-based representation with transformer for 3d object detection | NeurIPS · 2022 | [Paper](https://papers.nips.cc/paper_files/paper/2022/hash/752df938681b2cf15e5fc9689f0bcf3a-Abstract-Conference.html) · [Code](https://github.com/JIA-Lab-research/UVTR) | [35](REFERENCES.md#ref-035) |
| **HMFI** | Homogeneous multi-modal feature fusion and interaction for 3d object detection | ECCV · 2022 | [Paper](https://doi.org/10.1007/978-3-031-19839-7_40) | [36](REFERENCES.md#ref-036) |
| **SFD** | Sparse fuse dense: Towards high quality 3d detection with depth completion | CVPR · 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Wu_Sparse_Fuse_Dense_Towards_High_Quality_3D_Detection_With_Depth_CVPR_2022_paper.html) · [Code](https://github.com/LittlePey/SFD) | [37](REFERENCES.md#ref-037) |

**Additional methods discussed in the text**

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **Jiao et al. (metric-semantic mapping)** | Real-time metric-semantic mapping for autonomous navigation in outdoor environments | IEEE T-ASE · 2024 | [Paper](https://doi.org/10.1109/TASE.2024.3429280) | [130](REFERENCES.md#ref-130) |
| **MVX-Net (VoxelFusion variant)** | Mvx-net: Multimodal voxelnet for 3d object detection | ICRA · 2019 | [Paper](https://arxiv.org/abs/1904.01649) | [133](REFERENCES.md#ref-133) |

<a name="sec-3-3"></a>

## Region-level Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **AVOD** | Joint 3d proposal generation and object detection from view aggregation | IROS · 2018 | [Paper](https://arxiv.org/abs/1712.02294) · [Code](https://github.com/kujason/avod) | [38](REFERENCES.md#ref-038) |
| **RoarNet** | Roarnet: A robust 3d object detection based on region approximation refinement | IEEE IV · 2019 | [Paper](https://doi.org/10.1109/ivs.2019.8813895) | [39](REFERENCES.md#ref-039) |
| **TransFusion** | Transfusion: Robust lidar-camera fusion for 3d object detection with transformers | CVPR · 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Bai_TransFusion_Robust_LiDAR-Camera_Fusion_for_3D_Object_Detection_With_Transformers_CVPR_2022_paper.html) · [Code](https://github.com/XuyangBai/TransFusion) | [40](REFERENCES.md#ref-040) |
| **ConceptGraphs** | Conceptgraphs: Open-vocabulary 3d scene graphs for perception and planning | ICRA · 2024 | [Paper](https://doi.org/10.1109/ICRA57147.2024.10610243) · [Code](https://github.com/concept-graphs/concept-graphs) | [41](REFERENCES.md#ref-041) |
| **CMT-CNN** | Learning cross-modal deep representations for robust pedestrian detection | CVPR · 2017 | [Paper](https://doi.org/10.1109/cvpr.2017.451) | [42](REFERENCES.md#ref-042) |
| **AR-CNN** | Weakly aligned cross-modal learning for multispectral pedestrian detection | ICCV · 2019 | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Zhang_Weakly_Aligned_Cross-Modal_Learning_for_Multispectral_Pedestrian_Detection_ICCV_2019_paper.html) · [Code](https://github.com/luzhang16/AR-CNN) | [43](REFERENCES.md#ref-043) |
| **CAGTDet** | Improving RGB-infrared object detection with cascade alignment-guided transformer | Information Fusion · 2024 | [Paper](https://doi.org/10.1016/j.inffus.2024.102246) | [44](REFERENCES.md#ref-044) |
| **GAFF** | Guided attentive feature fusion for multispectral pedestrian detection | WACV · 2021 | [Paper](https://doi.org/10.1109/wacv48630.2021.00012) · [Code](https://github.com/zhanghengdev/GAFF) | [45](REFERENCES.md#ref-045) |
| **RSDet** | Removal and selection: Improving RGB-infrared object detection via coarse-to-fine fusion | arXiv · 2024 | [Paper](https://arxiv.org/abs/2401.10731) · [Code](https://github.com/Zhao-Tian-yi/RSDet) | [46](REFERENCES.md#ref-046) |

<a name="sec-3-4"></a>

## Multi-level Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **MMF** | Multi-task multi-sensor fusion for 3d object detection | CVPR · 2019 | [Paper](https://doi.org/10.1109/cvpr.2019.00752) | [47](REFERENCES.md#ref-047) |
| **EPNet** | Epnet: Enhancing point features with image semantics for 3d object detection | ECCV · 2020 | [Paper](https://link.springer.com/book/10.1007/978-3-030-58555-6) · [Code](https://github.com/happinesslz/EPNet) | [48](REFERENCES.md#ref-048) |
| **EPNet++** | Epnet++: Cascade bi-directional fusion for multi-modal 3d object detection | IEEE TPAMI · 2022 | [Paper](https://arxiv.org/abs/2112.11088) · [Code](https://github.com/happinesslz/EPNetV2) | [49](REFERENCES.md#ref-049) |
| **SPGNet** | Structure-Prior-Guided Multi-Stage Cross-Modal Collaborative Network for RGB-D Semantic Segmentation | Journal of Imaging · 2026 | [Paper](https://doi.org/10.3390/jimaging12080394) | [50](REFERENCES.md#ref-050) |
| **RCBEV** | Bridging the view disparity between radar and camera features for multi-modal fusion 3d object detection | IEEE T-IV · 2023 | [Paper](https://doi.org/10.1109/tiv.2023.3240287) | [51](REFERENCES.md#ref-051) |
| **DVF** | Dense voxel fusion for 3D object detection | WACV · 2023 | [Paper](https://doi.org/10.1109/wacv56688.2023.00073) · [Project](https://www.trailab.utias.utoronto.ca/3d-object-detection#:~:text=DVF%3A%20Dense%20Voxel%20Fusion%20for%203D%20Object%20Detection) | [52](REFERENCES.md#ref-052) |
| **LoGoNet** | Logonet: Towards accurate 3d object detection with local-to-global cross-modal fusion | CVPR · 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Li_LoGoNet_Towards_Accurate_3D_Object_Detection_With_Local-to-Global_Cross-Modal_Fusion_CVPR_2023_paper.html) · [Code](https://github.com/PJLab-ADG/LoGoNet) | [53](REFERENCES.md#ref-053) |
| **CAT-Det** | Cat-det: Contrastively augmented transformer for multi-modal 3d object detection | CVPR · 2022 | [Paper](https://openaccess.thecvf.com/content/CVPR2022/html/Zhang_CAT-Det_Contrastively_Augmented_Transformer_for_Multi-Modal_3D_Object_Detection_CVPR_2022_paper.html) | [54](REFERENCES.md#ref-054) |
| **SeaDATE** | SeaDATE: Remedy Dual-Attention Transformer with Semantic Alignment via Contrast Learning for Multimodal Object Detection | IEEE TCSVT · 2024 | [Paper](https://doi.org/10.1109/tcsvt.2024.3520318) | [55](REFERENCES.md#ref-055) |
| **CSSA** | Multimodal object detection by channel switching and spatial attention | CVPR · 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023W/PBVS/html/Cao_Multimodal_Object_Detection_by_Channel_Switching_and_Spatial_Attention_CVPRW_2023_paper.html) | [56](REFERENCES.md#ref-056) |
| **Fusion-Mamba** | Fusion-mamba for cross-modality object detection | arXiv · 2024 | [Paper](https://arxiv.org/abs/2404.09146) · [Code](https://github.com/EhanDong/Fusion-Mamba) | [57](REFERENCES.md#ref-057) |

**Additional methods discussed in the text**

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **Deep Continuous Fusion** | Deep continuous fusion for multi-sensor 3d object detection | ECCV · 2018 | [Paper](https://openaccess.thecvf.com/content_ECCV_2018/html/Ming_Liang_Deep_Continuous_Fusion_ECCV_2018_paper.html) | [131](REFERENCES.md#ref-131) |
| **Cross-Modality 3D Object Detection** | Cross-modality 3d object detection | WACV · 2021 | [Paper](https://doi.org/10.1109/wacv48630.2021.00382) | [132](REFERENCES.md#ref-132) |
| **Wang et al. (radar-camera obstacle avoidance)** | A deep-learning method based on the multistage fusion of radar and camera in uav obstacle avoidance | IEEE TAES · 2024 | [Paper](https://doi.org/10.1109/TAES.2024.3406495) | [134](REFERENCES.md#ref-134) |

<a name="sec-4-1"></a>

## Object-Level Temporal Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **ConceptGraphs** | Conceptgraphs: Open-vocabulary 3d scene graphs for perception and planning | ICRA · 2024 | [Paper](https://doi.org/10.1109/ICRA57147.2024.10610243) · [Code](https://github.com/concept-graphs/concept-graphs) | [41](REFERENCES.md#ref-041) |
| **StreamPETR** | Exploring Object-Centric Temporal Modeling for Efficient Multi-View 3D Object Detection | ICCV · 2023 | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Exploring_Object-Centric_Temporal_Modeling_for_Efficient_Multi-View_3D_Object_Detection_ICCV_2023_paper.html) · [Code](https://github.com/exiawsh/StreamPETR) | [58](REFERENCES.md#ref-058) |
| **SpaRC** | Sparc: Sparse radar-camera fusion for 3d object detection | ICRA · 2026 | [Paper](https://doi.org/10.1109/ICRA57385.2026.11696130) · [Project](https://phi-wol.github.io/sparc/) | [59](REFERENCES.md#ref-059) |
| **TempoCross** | TempoCross: instance-aware sparse representation for multimodal temporal fusion in 3D detection | Scientific Reports · 2026 | [Paper](https://www.nature.com/articles/s41598-026-62822-7) | [60](REFERENCES.md#ref-060) |
| **SpaRC-AD** | Sparc-ad: A baseline for radar-camera fusion in end-to-end autonomous driving | ICCV Workshops · 2025 | [Paper](https://doi.org/10.1109/ICCVW69036.2025.00193) | [61](REFERENCES.md#ref-061) |
| **SAM4D** | Sam4d: Segment anything in camera and lidar streams | ICCV · 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Xu_SAM4D_Segment_Anything_in_Camera_and_LiDAR_Streams_ICCV_2025_paper.html) · [Code](https://github.com/CN-ADLab/SAM4D) | [62](REFERENCES.md#ref-062) |
| **Adaptive LiDAR Scanning** | Adaptive LiDAR Scanning: Harnessing Temporal Cues for Efficient 3D Object Detection via Multi-Modal Fusion | AAAI · 2026 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/39735) | [63](REFERENCES.md#ref-063) |

<a name="sec-4-2"></a>

## Scene-Level Temporal Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **Q-TempFusion** | Q-TempFusion: Quantization-Aware Temporal Multi-Sensor Fusion on Bird's-Eye View Representation | WACV · 2025 | [Paper](https://openaccess.thecvf.com/content/WACV2025/html/Yu_Q-TempFusion_Quantization-Aware_Temporal_Multi-Sensor_Fusion_on_Birds-Eye_View_Representation_WACV_2025_paper.html) | [64](REFERENCES.md#ref-064) |
| **CRT-Fusion** | CRT-Fusion: Camera, Radar, Temporal Fusion Using Motion Information for 3D Object Detection | NeurIPS · 2024 | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c49a28241640407b23bba8f2495f4bc9-Abstract-Conference.html) · [Code](https://github.com/mjseong0414/CRT-Fusion) | [65](REFERENCES.md#ref-065) |
| **RaCFormer** | Racformer: Towards high-quality 3d object detection via query-based radar-camera fusion | CVPR · 2025 | [Paper](https://doi.org/10.1109/CVPR52734.2025.01592) · [Code](https://github.com/cxmomo/RaCFormer) | [66](REFERENCES.md#ref-066) |
| **RCTDistill** | Rctdistill: Cross-modal knowledge distillation framework for radar-camera 3d object detection with temporal fusion | ICCV · 2025 | [Paper](https://doi.org/10.1109/ICCV51701.2025.02348) | [67](REFERENCES.md#ref-067) |
| **CUT3R** | Continuous 3d perception model with persistent state | CVPR · 2025 | [Paper](https://doi.org/10.1109/CVPR52734.2025.00983) · [Code](https://github.com/CUT3R/CUT3R) | [68](REFERENCES.md#ref-068) |
| **STAC** | STAC: Plug-and-Play Spatio-Temporal Aware Cache Compression for Streaming 3D Reconstruction | CVPR · 2026 | [Project page](https://stac-3r.github.io/) · [Code](https://github.com/Rainzor/STAC) | [69](REFERENCES.md#ref-069) |
| **Doppler-SLAM** | Doppler-SLAM: Doppler-aided radar-inertial and LiDAR-inertial simultaneous localization and mapping | IEEE RA-L · 2025 | [Paper](https://doi.org/10.1109/LRA.2025.3595071) · [Project](https://github.com/Wayne-DWA/Doppler-SLAM) | [70](REFERENCES.md#ref-070) |
| **TEVIO** | TEVIO: Thermal-aided event-based visual–inertial odometry for robust state estimation in challenging environments | IEEE TIM · 2025 | [Paper](https://doi.org/10.1109/TIM.2025.3552392) | [71](REFERENCES.md#ref-071) |
| **SemanticFusion** | Semanticfusion: Dense 3d semantic mapping with convolutional neural networks | ICRA · 2017 | [Paper](https://doi.org/10.1109/ICRA.2017.7989538) · [Project](https://www.imperial.ac.uk/a-z-research/dyson-robotics-lab/projects/semanticfusion/) | [72](REFERENCES.md#ref-072) |
| **GS-LIVM** | GS-LIVM: Real-time photo-realistic LiDAR-Inertial-Visual mapping with Gaussian splatting | ICCV · 2025 | [Paper](https://doi.org/10.1109/ICCV51701.2025.02494) · [Code](https://github.com/xieyuser/GS-LIVM) | [73](REFERENCES.md#ref-073) |
| **LVI-GS** | LVI-GS: Tightly coupled LiDAR–visual–inertial SLAM using 3-D Gaussian splatting | IEEE TIM · 2025 | [Paper](https://doi.org/10.1109/TIM.2025.3551585) | [74](REFERENCES.md#ref-074) |
| **GS-LIVO** | GS-LIVO: Real-time LiDAR, inertial, and visual multisensor fused odometry with Gaussian mapping | IEEE T-RO · 2025 | [Paper](https://doi.org/10.1109/TRO.2025.3582809) · [Code](https://github.com/HKUST-Aerial-Robotics/GS-LIVO) | [75](REFERENCES.md#ref-075) |
| **RadarSplat-RIO** | RadarSplat-RIO: Indoor Radar-Inertial Odometry with Gaussian Splatting-Based Radar Bundle Adjustment | arXiv · 2026 | [Paper](https://arxiv.org/abs/2604.13492) | [76](REFERENCES.md#ref-076) |

<a name="sec-4-3"></a>

## Object–Scene Temporal Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **ConceptGraphs** | Conceptgraphs: Open-vocabulary 3d scene graphs for perception and planning | ICRA · 2024 | [Paper](https://doi.org/10.1109/ICRA57147.2024.10610243) · [Code](https://github.com/concept-graphs/concept-graphs) | [41](REFERENCES.md#ref-041) |
| **DovSG** | Dynamic open-vocabulary 3d scene graphs for long-term language-guided mobile manipulation | IEEE RA-L · 2025 | [Paper](https://doi.org/10.1109/LRA.2025.3547643) · [Code](https://github.com/BJHYZJ/DovSG) | [77](REFERENCES.md#ref-077) |
| **SPIN** | 3D dynamic scene graphs: Actionable spatial perception with places, objects, and humans | arXiv · 2020 | [Paper](https://arxiv.org/abs/2002.06289) · [Project](https://web.mit.edu/sparklab/2020/11/10/3D_Dynamic_Scene_Graphs__Actionable_Spatial_Perception_with_Places__Objects__and_Humans.html) | [78](REFERENCES.md#ref-078) |
| **Hydra** | Hydra: A real-time spatial perception system for 3D scene graph construction and optimization | arXiv · 2022 | [Paper](https://arxiv.org/abs/2201.13360) · [Code](https://github.com/MIT-SPARK/Hydra) | [79](REFERENCES.md#ref-079) |
| **Khronos** | Khronos: A unified approach for spatio-temporal metric-semantic slam in dynamic environments | arXiv · 2024 | [Paper](https://arxiv.org/abs/2402.13817) · [Code](https://github.com/MIT-SPARK/Khronos) | [80](REFERENCES.md#ref-080) |

<a name="sec-5-1"></a>

## Collaborative Fusion

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **V2VNet** | V2vnet: Vehicle-to-vehicle communication for joint perception and prediction | ECCV · 2020 | [Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470596.pdf) | [81](REFERENCES.md#ref-081) |
| **CoBEVT** | Cobevt: Cooperative bird's eye view semantic segmentation with sparse transformers | arXiv · 2022 | [Paper](https://arxiv.org/abs/2207.02202) · [Code](https://github.com/DerrickXuNu/CoBEVT) | [82](REFERENCES.md#ref-082) |
| **CoCa3D** | Collaboration helps camera overtake lidar in 3d detection | CVPR · 2023 | [Paper](https://openaccess.thecvf.com/content/CVPR2023/html/Hu_Collaboration_Helps_Camera_Overtake_LiDAR_in_3D_Detection_CVPR_2023_paper.html) · [Code](https://github.com/MediaBrain-SJTU/CoCa3D) | [83](REFERENCES.md#ref-083) |
| **UCDNet** | Ucdnet: Multi-uav collaborative 3-d object detection network by reliable feature mapping | IEEE TGRS · 2024 | [Paper](https://ieeexplore.ieee.org/document/10802930/) | [84](REFERENCES.md#ref-084) |
| **HM-ViT** | HM-ViT: Hetero-modal vehicle-to-vehicle cooperative perception with vision transformer | ICCV · 2023 | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Xiang_HM-ViT_Hetero-Modal_Vehicle-to-Vehicle_Cooperative_Perception_with_Vision_Transformer_ICCV_2023_paper.html) · [Code](https://github.com/XHwind/HM-ViT) | [85](REFERENCES.md#ref-085) |
| **MCOP** | MCOP: Multi-UAV Collaborative Occupancy Prediction | ICCV · 2025 | [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Lin_MCOP_Multi-UAV_Collaborative_Occupancy_Prediction_ICCV_2025_paper.html) | [86](REFERENCES.md#ref-086) |
| **MRCNet** | Multi-agent Collaborative Perception via Motion-aware Robust Communication Network | CVPR · 2024 | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Hong_Multi-agent_Collaborative_Perception_via_Motion-aware_Robust_Communication_Network_CVPR_2024_paper.html) | [87](REFERENCES.md#ref-087) |

**Additional methods discussed in the text**

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **Gao et al. (cross-view place recognition)** | Visual, spatial, geometric-preserved place recognition for cross-view and cross-modal collaborative perception | IROS · 2023 | [Paper](https://doi.org/10.1109/IROS55552.2023.10341898) | [135](REFERENCES.md#ref-135) |

<a name="sec-5-2"></a>

## Agent-to-Agent Communication

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **When2com** | When2com: Multi-agent perception via communication graph grouping | CVPR · 2020 | [Paper](https://doi.org/10.1109/CVPR42600.2020.00416) · [Code](https://github.com/GT-RIPL/MultiAgentPerception) | [88](REFERENCES.md#ref-088) |
| **Who2com** | Who2com: Collaborative perception via learnable handshake communication | ICRA · 2020 | [Paper](https://doi.org/10.1109/ICRA40945.2020.9197364) · [Project](https://ycliu93.github.io/projects/multi-agent-perception.html) | [89](REFERENCES.md#ref-089) |
| **How2comm** | How2comm: Communication-efficient and collaboration-pragmatic multi-agent perception | NeurIPS · 2024 ([2023 proceedings](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4f31327e046913c7238d5b671f5d820e-Abstract.html)) | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4f31327e046913c7238d5b671f5d820e-Abstract.html) · [Code](https://github.com/ydk122024/How2comm) | [90](REFERENCES.md#ref-090) |
| **Where2comm** | Where2comm: Communication-efficient collaborative perception via spatial confidence maps | NeurIPS · 2022 | [Paper](https://papers.neurips.cc/paper_files/paper/2022/hash/1f5c5cd01b864d53cc5fa0a3472e152e-Abstract-Conference.html) · [Code](https://github.com/MediaBrain-SJTU/Where2comm) | [91](REFERENCES.md#ref-091) |
| **CodeFilling** | Communication-Efficient Collaborative Perception via Information Filling with Codebook | CVPR · 2024 | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Hu_Communication-Efficient_Collaborative_Perception_via_Information_Filling_with_Codebook_CVPR_2024_paper.html) · [Code](https://github.com/PhyllisH/CodeFilling) | [92](REFERENCES.md#ref-092) |
| **MR-COGraphs** | MR-COGraphs: Communication-efficient multi-robot open-vocabulary mapping system via 3D scene graphs | IEEE RA-L · 2025 | [Paper](https://doi.org/10.1109/LRA.2025.3561569) · [Project](https://github.com/efc-robot/MR-COGraphs) | [93](REFERENCES.md#ref-093) |
| **MACP** | MACP: Efficient model adaptation for cooperative perception | WACV · 2024 | [Paper](https://openaccess.thecvf.com/content/WACV2024/papers/Ma_MACP_Efficient_Model_Adaptation_for_Cooperative_Perception_WACV_2024_paper.pdf) · [Code](https://github.com/PurdueDigitalTwin/MACP) | [94](REFERENCES.md#ref-094) |

<a name="sec-6-1"></a>

## Vision–Language Models

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **SpatialVLM** | Spatialvlm: Endowing vision-language models with spatial reasoning capabilities | CVPR · 2024 | [Paper](https://doi.org/10.1109/CVPR52733.2024.01370) · [Project](https://spatial-vlm.github.io/) | [95](REFERENCES.md#ref-095) |
| **RoboPoint** | RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics | arXiv · 2024 | [Paper](https://arxiv.org/abs/2406.10721) · [Code](https://github.com/wentaoyuan/RoboPoint) | [96](REFERENCES.md#ref-096) |
| **DriveLM** | Drivelm: Driving with graph visual question answering | ECCV · 2024 | [Paper](https://doi.org/10.1007/978-3-031-72943-0_15) · [Code](https://github.com/OpenDriveLab/DriveLM) | [97](REFERENCES.md#ref-097) |
| **DriveVLM** | DriveVLM: the convergence of autonomous driving and large vision-language models. arXiv preprint | arXiv · 2024 | [Paper](https://tsinghua-mars-lab.github.io/DriveVLM/DriveVLM.pdf) · [Project](https://tsinghua-mars-lab.github.io/DriveVLM/) | [98](REFERENCES.md#ref-098) |

<a name="sec-6-2"></a>

## LLMs with Other Sensor Modalities

| Method | Paper title | Venue · year as cited | Resources | Ref. |
| --- | --- | --- | --- | ---: |
| **LiDAR-LLM** | Lidar-llm: Exploring the potential of large language models for 3d lidar understanding | AAAI · 2025 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/download/33001/35156) · [Project](https://sites.google.com/view/lidar-llm) | [99](REFERENCES.md#ref-099) |
| **TOD3Cap** | Tod3cap: Towards 3d dense captioning in outdoor scenes | ECCV · 2024 | [Paper](https://doi.org/10.1007/978-3-031-72649-1_21) · [Code](https://github.com/jxbbb/TOD3Cap) | [100](REFERENCES.md#ref-100) |
| **BEV-LLM** | BEV-LLM: Leveraging multimodal BEV maps for scene captioning in autonomous driving | IEEE IV · 2025 | [Paper](https://doi.org/10.1109/IV64158.2025.11097781) | [101](REFERENCES.md#ref-101) |
| **MAPLM** | Maplm: A real-world large-scale vision-language benchmark for map and traffic scene understanding | CVPR · 2024 | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Cao_MAPLM_A_Real-World_Large-Scale_Vision-Language_Benchmark_for_Map_and_Traffic_CVPR_2024_paper.html) · [Code](https://github.com/LLVM-AD/MAPLM) | [102](REFERENCES.md#ref-102) |
| **Talk2BEV** | Talk2bev: Language-enhanced bird’s-eye view maps for autonomous driving | ICRA · 2024 | [Paper](https://doi.org/10.1109/ICRA57147.2024.10611485) · [Code](https://github.com/llmbev/talk2bev) | [103](REFERENCES.md#ref-103) |
| **VLMaterial** | VLMaterial: Vision-Language Model-Based Camera-Radar Fusion for Physics-Grounded Material Identification | arXiv · 2026 | [Paper](https://arxiv.org/abs/2604.11671) | [104](REFERENCES.md#ref-104) |
| **FuseLID** | FuseLID: Vision-Language Model-Based Camera-Radar Fusion for Liquid Identification | UbiComp Companion · 2025 | [Paper](https://doi.org/10.1145/3714394.3756291) | [105](REFERENCES.md#ref-105) |
| **CRaFT-SD** | Camera-Radar Data Based Vision Language Model for Automotive Driving Scene Description | IEEE Sensors Journal · 2026 | [Paper](https://doi.org/10.1109/JSEN.2026.3692542) | [106](REFERENCES.md#ref-106) |
| **DUALVISION** | DUALVISION: RGB-Infrared Multimodal Large Language Models for Robust Visual Reasoning | arXiv · 2026 | [Paper](https://arxiv.org/abs/2604.18829) · [Code](https://github.com/abrarmajeedi/DualVision) | [107](REFERENCES.md#ref-107) |
| **Thermo-VL** | Thermo-VL: Extending Vision-Language Models to Thermal Infrared Perception | arXiv · 2026 | [Paper](https://arxiv.org/abs/2605.21882) · [Project](https://thusharakart.github.io/Thermo-VL) | [108](REFERENCES.md#ref-108) |
| **FireMM-IR** | FireMM-IR: An Infrared-Enhanced Multi-Modal Large Language Model for Comprehensive Scene Understanding in Remote Sensing Forest Fire Monitoring | Sensors · 2026 | [Paper](https://doi.org/10.3390/s26020390) | [109](REFERENCES.md#ref-109) |
| **Wang et al.** | Infrared and visible image fusion driven by multimodal large language models | Frontiers in Physics · 2025 | [Paper](https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2025.1599937/full) | [110](REFERENCES.md#ref-110) |
