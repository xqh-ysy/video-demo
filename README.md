# video-demo
Here are some saliency prediction results comparing PASSNET with ground truth (GT). We have selected representative videos to demonstrate the effectiveness of our method. You can **download** and **then review** them. Thank you for your interest in our work！<br>
**Descriptions**<br>


| File Name                      | Description                                |
|--------------------------------|--------------------------------------------|
| `ablation-pre-3_50_O_S.mp4`    | Saliency prediction (MESI only)            |
| `OnlyVis_3_50_O_S.mp4`         | Saliency prediction (VSTA only)            |
| `SVGC_L15.mp4`         | Saliency prediction (SVGC 2024)            |
| `AVISAL_L15.mp4`         | Saliency prediction (AVISAL 2025)            |
| `pre-3_50_O_S.mp4`            | Saliency prediction (MESI + RSSI)          |
| `gt-xx.mp4`                    | Ground truth (GT) video                    |
| `pre-xx.mp4`                   | Predicted saliency video                   |

## 📁 Large File Access
> 💡 **L55 video files** are stored in the dedicated [`lfs-video` branch](https://github.com/xqh-ysy/video-demo/tree/lfs-video) using Git LFS.

---

## 🎥 Model Prediction Visualizations

### 🔍 Cross-Dataset Comparisons
- **YQ-ODV Dataset**  
  [Multi-frame model comparison](https://github.com/user-attachments/files/19911588/multi-output-final-re.pdf)  
  ![](https://via.placeholder.com/600x100/FFEE99/000?text=YQ-ODV+Preview)

- **AVS-ODV Dataset**  
  [Cross-model prediction analysis](https://github.com/user-attachments/files/19911600/multi-SAL-ODV.pdf)<br>
  ![](https://via.placeholder.com/600x100/C3E4CD/000?text=AVS-ODV+Preview)

- **360AV-HM Scenarios**  
  [Five-scenario comparison](https://github.com/user-attachments/files/19911663/1108chao.pdf)  
  ![](https://via.placeholder.com/600x100/D4E6F1/000?text=360AV-HM+Scenarios)

---
## 🔬 Fusion Stage Analysis

### 🧩 Modality Experiments
- **Visualizing saliency results with different modalities.**<br>
  [Different modalities](https://github.com/user-attachments/files/19911708/ablationfinal.pdf)



### 🎵 Audio-Visual Correlation prediction((MESI -> RSSI))
- **Visualization of saliency results at different fusion stages in scenes with changing guitar sounds.**<br>
  [Audio-visual saliency mapping](https://github.com/user-attachments/files/19911711/1024finalfigure.pdf)  
  ![](https://via.placeholder.com/400x80/D7BDE2/000?text=Guitar+Sound+Correlation)
- **Visualizing the saliency results with different fusion stages**<br>
  [Stage-by-stage comparison](https://github.com/user-attachments/files/19911710/930ABL.1.pdf)<br>
  ![](https://via.placeholder.com/400x80/FFE5B4/000?text=Fusion+Stages)
- **Vsualizing saliency results at different fusion stages in scenes with a human shifting from a distance**<br>
  [Spatial-temporal dynamics](https://github.com/user-attachments/files/19912054/multi-ablation-RES.pdf)  
  ![](https://via.placeholder.com/400x80/F5CBA7/000?text=Human+Distance+Analysis)




📝**Abstract**<br>

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
<br>
<br>


<img width="665" alt="image" src="https://github.com/user-attachments/assets/0ce037c3-29c1-49ca-89e8-557dc828c395" />







