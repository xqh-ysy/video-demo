# video-demo
Here are some saliency prediction results comparing PASSNET with ground truth (GT). We have selected representative videos to demonstrate the effectiveness of our method. You can download and review them. Thank you for your interest in our work！<br>
**Descriptions**<br>


| File Name                      | Description                                |
|--------------------------------|--------------------------------------------|
| `ablation-pre-3_50_O_S.mp4`    | Saliency prediction (MESI only)            |
| `pre-3_50_O_S.mp4`            | Saliency prediction (MESI + RSSI)          |
| `gt-xx.mp4`                    | Ground truth (GT) video                    |
| `pre-xx.mp4`                   | Predicted saliency video                   |

> 💡 Large L55 video files are in the [`lfs-video` branch](https://github.com/xqh-ysy/video-demo/tree/lfs-video).


**Abstract**<br>
<br>
Since the interaction between audio and visual in
panoramic video affects the user’s immersive experience, the
research of incorporating audio into panoramic video saliency
prediction has attracted much attention. However, there are
still many challenges, including inadequate calibration between
the temporal semantics of audio and the spatial perception
of video frames in complex scenes, as well as difficulties in
managing abrupt audio scene changes in long-term videos. In
this paper, we propose a **Progressive Audio-Visual Semantic
Spatial-Aware Network (PASSNet)** for panoramic video saliency
predition, which includes a visual module, an audio module,
and a fusion module. The visual module introduces a spherical
vision transformer to solve the distortion of the panoramic
video projection and the perception of the over-the-horizon.
For the audio module, we propose the audio semantic temporal
attention submodule to capture the contextual information of the
audio by introducing temporal location encoding. In the fusion
module, a novel two-stage audio-visual fusion strategy is em-
ployed, which progressively optimizes the precise and exhaustive
understanding of audio temporal semantic information with over-
the-horizon spatial perception through cross-modal interactions.
Quantitative and visualization experiments demonstrate that
our PASSNet outperforms the state-of-the-art methods on two
publicly available datasets. Further ablation experiments also
validate the effectiveness of our proposed modules in effectively
capturing both audio and visual features for saliency prediction
in panoramic videos.



<img width="665" alt="image" src="https://github.com/user-attachments/assets/0ce037c3-29c1-49ca-89e8-557dc828c395" />
