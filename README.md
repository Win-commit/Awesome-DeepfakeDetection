# Awesome-DeepfakeDetection
A Paper List for Deepfake-Detection Research.
Given a video w or w/o audio,decide it's true or false, False audio,True video/False video,True audio/False video,False audio/True audio,True video.

The videos fault includes ：Swap face, remove entity, adding entity, tempory edit(Inter-Frame Manipulations), Background/Color cahnge , text changed(last five categories from Videoshame)

The audio fault includes : audio manipulation,audio changed/added

# Awesome papers
## Unimodel Deepfake Detection
These models use unimodel features to do detect,either video features or audio features.

|  Title  |   Venue  |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|
|[VideoFACT: Detecting Video Forgeries Using Attention, Scene Context, and Forensic Traces](https://arxiv.org/abs/2211.15775) | WACV,2024 | [github](https://github.com/ductai199x/videofact-wacv-2024) |-|
|[E3: Ensemble of Expert Embedders for Adapting Synthetic Image Detectors to New Generators Using Limited Data](https://arxiv.org/abs/2404.08814) | CVPR Workshop,2024 | [github](https://github.com/ArefAz/E3-Ensemble-of-Expert-Embedders-CVPRWMF24)|-|


## Multi-model Deepfake Detection
These models use both video and audio features to do detect false video or false audio. And actually, **the main task in this way is how to efficiently learn the audio-vision features , a subset of multimodal features learning**
|  Title  |   Venue  |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|
|[AVFF: Audio-Visual Feature Fusion for Video Deepfake Detection](https://arxiv.org/abs/2406.02951v1)| CVPR,2024 | - | - |
|[Recurrent Convolutional Structures for Audio Spoof and Video Deepfake Detection](https://ieeexplore.ieee.org/abstract/document/9105097) | TSP,2020 | [github](https://github.com/nviable/xcepttemporal-deepfake-detection) | - |
|[PVASS-MDD: Predictive Visual-audio Alignment Self-supervision for Multimodal Deepfake Detection](https://ieeexplore.ieee.org/abstract/document/10233898)| TCSVT,2023| - | - |
|[Not made for each other– Audio-Visual Dissonance-based Deepfake Detection and Localization](https://arxiv.org/pdf/2005.14405v3) | ACM MM,2020 | [github](https://github.com/abhinavdhall/deepfake)| - |
|[Joint Audio-Visual Deepfake Detection](https://openaccess.thecvf.com//content/ICCV2021/papers/Zhou_Joint_Audio-Visual_Deepfake_Detection_ICCV_2021_paper.pdf) | ICCV,2021| - | - |
|[FUSION AND ORTHOGONAL PROJECTION FOR IMPROVED FACE-VOICE ASSOCIATION](https://arxiv.org/pdf/2208.10238v1) | ICASSP,2022| [github](https://github.com/msaadsaeed/FOP) | - |
|[CONTRASTIVE AUDIO-VISUAL MASKED AUTOENCODER](https://arxiv.org/abs/2210.07839) | ICLR,2023 | [github](https://github.com/yuangongnd/cav-mae)| - |
|[AVoiD-DF: Audio-Visual Joint Learning for Detecting Deepfake](https://ieeexplore.ieee.org/document/10081373) |  TIFS,2023 | [github](https://github.com/SYSU-DISG/AVoiD-DF)| - |
|[Lost in Translation: Lip-Sync Deepfake Detection from Audio-Video Mismatch](https://arxiv.org/abs/2401.15668v1) | CVPR Workshop,2024 | - | - |

## Anomaly detection

Disharmonious sounds or videos, as well as their mismatches, can be regarded as anomalous segments in time series. Therefore, deepfake detection can be considered as a time series anomaly detection task
|  Title  |   Venue  |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|
|[Self-Supervised Video Forensics by Audio-Visual Anomaly Dete](https://arxiv.org/abs/2301.01767) | CVPR,2023 | [github](https://github.com/cfeng16/audio-visual-forensics)|[demo](https://cfeng16.github.io/audio-visual-forensics/)


## Survey

|  Title  |   Venue  | 
|:--------|:--------:|
|[Generation and detection of manipulated multimodal audiovisual content:Advances, trends and open challenges](https://www.sciencedirect.com/science/article/pii/S1566253523004190) | Information Fusion,2024 |
|[Deepfake Generation and Detection: A Benchmark and Survey](https://arxiv.org/abs/2403.17881) | arxiv,2024 | - |



## Commonly used test sets

| Title | Link | Source Link |  
|:------|:-----|:--------------|
|[Videosham](https://arxiv.org/abs/2207.13064) | - | [source](https://github.com/adobe-research/VideoSham-dataset) |

# The tools  creating pipeline to general deepfake
## Video to audio generation
|  Title  |   Venue  |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|
| [Seeing and Hearing: Open-domain Visual-Audio Generation with Diffusion Latent Aligners](https://arxiv.org/abs/2402.17723) | CVPR2024 | [github](https://github.com/yzxing87/Seeing-and-Hearing) | [demo](https://yzxing87.github.io/Seeing-and-Hearing/) |
|[Diff-Foley: Synchronized Video-to-Audio Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2306.17203v1) | Nips2023 | [github](https://github.com/luosiallen/Diff-Foley?tab=readme-ov-file)| [demo](https://huggingface.co/SimianLuo/Diff-Foley) |

## Segment and inpainting
|  Title  |   Venue  |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|
|[SAM 2: Segment Anything in Images and Videos](https://ai.meta.com/research/publications/sam-2-segment-anything-in-images-and-videos/)| Meta | [github](https://github.com/facebookresearch/segment-anything-2?tab=readme-ov-file) | [demo](https://sam2.metademolab.com/)
|[E2FGVI:Towards An End-to-End Framework for Flow-Guided Video Inpainting](https://arxiv.org/abs/2204.02663) | CVPR2022 |[github](https://github.com/MCG-NKU/E2FGVI/tree/master) | [demo](https://www.youtube.com/watch?v=N--qC3T2wc4)
|[ProPainter: Improving Propagation and Transformer for Video Inpainting](https://arxiv.org/abs/2309.03897)|ICCV2023|[github](https://github.com/sczhou/propainter)|[demo](https://huggingface.co/spaces/sczhou/ProPainter)
