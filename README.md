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



## Multi-model Deepfake Detection
These models use both video and audio features to do detect false video or false audio. And actually, **the main task in this way is how to efficiently learn the audio-vision features , a subset of multimodal features learning**
|  Title  |   Venue  |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|
|[AVFF: Audio-Visual Feature Fusion for Video Deepfake Detection](https://arxiv.org/abs/2406.02951v1)| CVPR,2024 | - | - |
|[Recurrent Convolutional Structures for Audio Spoof and Video Deepfake Detection](https://ieeexplore.ieee.org/abstract/document/9105097) | IEEE Journal of Selected Topics in Signal Processing,2020 | [github](https://github.com/nviable/xcepttemporal-deepfake-detection) | - |
|[PVASS-MDD: Predictive Visual-audio Alignment Self-supervision for Multimodal Deepfake Detection](https://ieeexplore.ieee.org/abstract/document/10233898)| IEEE TCSVT,2023| - | - |
|[Not made for each other– Audio-Visual Dissonance-based Deepfake Detection and Localization](https://arxiv.org/pdf/2005.14405v3) | ACM MM,2020 | [github](https://github.com/abhinavdhall/deepfake)| - |
|[Joint Audio-Visual Deepfake Detection](https://openaccess.thecvf.com//content/ICCV2021/papers/Zhou_Joint_Audio-Visual_Deepfake_Detection_ICCV_2021_paper.pdf) | ICCV,2021| - | - |
|[FUSION AND ORTHOGONAL PROJECTION FOR IMPROVED FACE-VOICE ASSOCIATION](https://arxiv.org/pdf/2208.10238v1) | ICASSP,2022| [github](https://github.com/msaadsaeed/FOP) | - |
|[CONTRASTIVE AUDIO-VISUAL MASKED AUTOENCODER](https://arxiv.org/abs/2210.07839) | ICLR,2023 | [github](https://github.com/yuangongnd/cav-mae.)| - |
|[AVoiD-DF: Audio-Visual Joint Learning for Detecting Deepfake]() |  TIFS,2023 | [github](https://github.com/SYSU-DISG/AVoiD-DF)| - |

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



