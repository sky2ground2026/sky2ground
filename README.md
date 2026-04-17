<div align="center">

# Sky2Ground: A Benchmark for Site Modeling under Varying Altitude


<p align="center">
  <b>Zengyan Wang</b>, <b>Sirshapan Mitra</b>, <a href="https://rajatmodi62.github.io/2026/04/09/sky2ground/"><b>Rajat Modi</b></a>, <b>Grace Lim</b>, <b>Yogesh Rawat</b>
  <br>
  <strong>CVPR 2026</strong>
  <br>
  <a href="https://arxiv.org/abs/2603.13740">[arXiv]</a> | <a href="https://www.kaggle.com/datasets/zhyw86/varying-altitude-dataset">[Dataset]</a> | <a href="https://github.com/zhyw86/Sky2Ground">[Code]</a>
</p>

## 🖼 Dataset Preview

Our dataset bridges the gap between synthetic environments and real-world captures. Below are samples of the multi-view perspectives provided.

### 🌐 Synthetic Dataset (GIF Samples)
*Generated environments featuring a full 5-view suite.*

<p align="center">
  <img src="gif/ID0004_satellite.gif" width="19%" title="Synthetic Satellite">
  <img src="gif/ID0004_left.gif" width="19%" title="Synthetic Aerial Left">
  <img src="gif/ID0004.gif" width="19%" title="Synthetic Aerial Center">
  <img src="gif/ID0004_right.gif" width="19%" title="Synthetic Aerial Right">
  <img src="gif/ID0004_street.gif" width="19%" title="Synthetic Street View">
  <br>
  <em>Satellite | Aerial L | Aerial C | Aerial R | Street View</em>
</p>

---

### 📸 Real-World Dataset (Static Images)
*Authentic captures for domain validation.*

<p align="center">
  <img src="imgs/ID0004_sat_real_19.jpg" width="32%" title="Real Satellite">
  <img src="imgs/aerial_014.jpg" width="32%" title="Real Aerial 1">
  <img src="imgs/aerial_019.jpg" width="32%" title="Real Aerial 2">
  <br>
  <img src="imgs/street_003.jpg" width="32%" title="Real Street View 1">
  <img src="imgs/street_033.jpg" width="32%" title="Real Street View 2">
  <img src="imgs/street_120.jpg" width="32%" title="Real Street View 3">
  <br>
  <em>Top: Satellite & Aerial Views | Bottom: Street Views</em>
</p>

> **Note:** Real-world samples are provided as high-resolution static images, while synthetic samples include dynamic transitions (GIFs) to demonstrate environmental variance.

## 🚀 Access the Dataset

| Platform | Link | Recommended For |
| :--- | :--- | :--- |
| **Hugging Face** | [🤗 Under Construction](https://huggingface.co/datasets/letsGoBlind/Sky2Ground/tree/main) | Large-scale streaming |
| **Kaggle** | [📁 Under Construction](https://www.kaggle.com/datasets/zhyw86/varying-altitude-dataset) | Notebooks & Competitions |

---

## 🛠 Project Progress

- [x] Synthetic Images
- [ ] Real Images
- [ ] Benchmark

## Citation

```bibtex
@misc{wang2026sky2groundbenchmarksitemodeling,
      title={Sky2Ground: A Benchmark for Site Modeling under Varying Altitude}, 
      author={Zengyan Wang and Sirshapan Mitra and Rajat Modi and Grace Lim and Yogesh Rawat},
      year={2026},
      eprint={2603.13740},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={[https://arxiv.org/abs/2603.13740](https://arxiv.org/abs/2603.13740)}
}
