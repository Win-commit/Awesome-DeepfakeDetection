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
|[Joint Audio-Visual Deepfake Detection](https://openaccess.thecvf.com//content/ICCV2021/papers/Zhou_Joint_Audio-Visual_Deepfake_Detection_ICCV_2021_paper.pdf) | ICCV,2021|-|-|

## Survey

|  Title  |   Venue  | 
|:--------|:--------:|
|[Generation and detection of manipulated multimodal audiovisual content:Advances, trends and open challenges](https://www.sciencedirect.com/science/article/pii/S1566253523004190) | Information Fusion,2024 |



