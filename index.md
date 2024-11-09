---
layout: default
---
The SpoofCeleb dataset is the result of a collaborative effort leveraging the [TITW](https://arxiv.org/abs/2409.08711) dataset.
TITW systematically segments, filters, and enhances human speech samples derived from the [VoxCeleb](https://mm.kaist.ac.kr/datasets/voxceleb/) dataset.
Using TITW, 23 Text-to-Speech (TTS) systems have been trained.
SpoofCeleb includes both authentic human speech from TITW and synthetic versions generated using these 23 TTS models.

# Data Access
The dataset is currently hosted on Hugging Face. Access is granted upon request and agreement to the terms of use.
Once the request is approved by the authors, you can download the dataset using the following instructions.

## How to Download
Before downloading, ensure that you have installed the huggingface-cli tool and logged in via:
- The user needs to install `huggingface-cli` and login via `huggingface-cli login`.
- For further setup guidelines, refer to the [link](https://huggingface.co/docs/hub/repositories-getting-started).

To download the dataset:
```python
huggingface-cli download --repo-type dataset jungjee/spoofceleb
```

# License
The SpoofCeleb dataset is available to download under a Creative Commons Attribution 4.0 International License. The copyright of the human speech files remains with the original owners of the video.

# Publication
If you find the SpoofCeleb dataset useful in your research, please consider citing the following paper:

```bibtex
@article{jung2024spoofceleb,
  title={SpoofCeleb: Speech Deepfake Detection and SASV In The Wild},
  author={Jung, Jee-weon and Wu, Yihan and Wang, Xin and Kim, Ji-Hoon and Maiti, Soumi and Matsunaga, Yuta and Shim, Hye-jin and Tian, Jinchuan and Evans, Nicholas and Chung, Joon Son and others},
  journal={arXiv preprint arXiv:2409.17285},
  year={2024}
}
```
```bibtex
@article{jung2024text,
  title={Text-To-Speech Synthesis In The Wild},
  author={Jung, Jee-weon and Zhang, Wangyou and Maiti, Soumi and Wu, Yihan and Wang, Xin and Kim, Ji-Hoon and Matsunaga, Yuta and Um, Seyun and Tian, Jinchuan and Shim, Hye-jin and others},
  journal={arXiv preprint arXiv:2409.08711},
  year={2024}
}
```
