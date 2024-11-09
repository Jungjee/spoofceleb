---
layout: default
---
The SpoofCeleb is a result of combined effort with the [TITW](https://arxiv.org/abs/2409.08711) dataset.
The TITW dataset segments, filters, and enhances human speech samples in the [VoxCeleb](https://mm.kaist.ac.kr/datasets/voxceleb/) dataset.
Using TITW, 23 Text-to-Speech (TTS) systems have been trained.
SpoofCeleb consists of human speech from TITW and synthetic versions of TITW generated from the trained 23 TTS systems.

# Access to data
Currently, the dataset is hosted at HuggingFace.
Once request to data has been received with agreement to the terms,
the authors will review and approve access.

Once granted, below code will download the dataset.
- The user needs to install `huggingface-cli` and login via `huggingface-cli login`.
- Refer to [link](https://huggingface.co/docs/hub/repositories-getting-started) for guidelines.

```python
huggingface-cli download --repo-type dataset jungjee/spoofceleb
```

# License
The SpoofCeleb dataset is available to download under a Creative Commons Attribution 4.0 International License. The copyright of the human speech files remains with the original owners of the video.

# Publication

Please consider citing the below papers if you make use of the SpoofCeleb dataset.

```bibtex
@article{jung2024spoofceleb,
  title={SpoofCeleb: Speech Deepfake Detection and SASV In The Wild},
  author={Jung, Jee-weon and Wu, Yihan and Wang, Xin and Kim, Ji-Hoon and Maiti, Soumi and Matsunaga, Yuta and Shim, Hye-jin and Tian, Jinchuan and Evans, Nicholas and Chung, Joon Son and others},
  journal={arXiv preprint arXiv:2409.17285},
  year={2024}
}
```
