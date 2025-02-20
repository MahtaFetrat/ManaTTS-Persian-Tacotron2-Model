# ManaTTS-Persian-Tacotron2-Model

This repository provides the inference pipeline and resources for a Persian Text-to-Speech (TTS) model trained on the [**ManaTTS dataset**](https://huggingface.co/datasets/MahtaFetrat/Mana-TTS), the largest publicly accessible single-speaker Persian corpus. The dataset comprises over 100 hours of high-quality audio (44.1 kHz) sourced from the [**Nasl-e-Mana magazine**](https://naslemana.com/). The model is based on the [Tacotron2 architecture](https://github.com/MahtaFetrat/Persian-MultiSpeaker-Tacotron2/) and is designed to generate natural and high-quality Persian speech.

**Model Weights**: The trained model weights are hosted on Hugging Face. You can access them here: [Persian-Tacotron2-on-ManaTTS](https://huggingface.co/MahtaFetrat/Persian-Tacotron2-on-ManaTTS).

---

## Inference

You can use the provided inference notebook to generate speech from text.

### Inference Notebook:
- **GitHub Notebook**: [inference.ipynb](inference.ipynb)
- **Google Colab**: [Open in Colab](https://colab.research.google.com/drive/1e0BYsfMKRiikaA62umEyZejmivn0tTE8?usp=sharing)
- 
---

## Ethical Use

The ManaTTS dataset and model are provided exclusively for research and development purposes. We emphasize the critical importance of ethical conduct in utilizing this dataset. Please refrain from any misuse, including but not limited to voice impersonation, identity theft, or fraudulent activities.

By accessing and using the ManaTTS dataset and model, you are obligated to uphold the highest standards of integrity and respect for user privacy. Any violation of these principles may have severe legal and ethical consequences.

---

## Acknowledgments

We would like to express our sincere gratitude to [**Nasl-e-Mana**](https://naslemana.com/), the monthly magazine of the blind community of Iran, for their generosity. Their commitment to openness and collaboration has been instrumental in advancing research and development in speech synthesis. We are especially thankful for their choice to release the data under the **Creative Commons CC-0 license**, allowing for unrestricted use and distribution.

---

## References

- **ManaTTS Dataset**: [Hugging Face Dataset](https://huggingface.co/datasets/MahtaFetrat/Mana-TTS) | [GitHub Repository](https://github.com/MahtaFetrat/ManaTTS-Persian-Speech-Dataset)
- **Tacotron2 Implementation**: [GitHub Repository](https://github.com/MahtaFetrat/Persian-MultiSpeaker-Tacotron2/)
- **Model Weights**: [Hugging Face Model Repository](https://huggingface.co/MahtaFetrat/Persian-Tacotron2-on-ManaTTS)

---

## License

The model weights are licensed under **CC0-1.0**, the same license as the ManaTTS dataset. 

The model implementation is based on [Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning), which is licensed under the **MIT License**. Below is the copyright statement for the original and modified works:

```
Modified & original work Copyright (c) 2019 Corentin Jemine (https://github.com/CorentinJ)  
Original work Copyright (c) 2018 Rayhane Mama (https://github.com/Rayhane-mamah)  
Original work Copyright (c) 2019 fatchord (https://github.com/fatchord)  
Original work Copyright (c) 2015 braindead (https://github.com/braindead)  
Modified work Copyright (c) 2025 Majid Adibian (https://github.com/Adibian)  
Modified work Copyright (c) 2025 Mahta Fetrat (https://github.com/MahtaFetrat)
```

---

## Citation

If you use the ManaTTS dataset or this model in your research, please cite the following paper:

```bibtex
@article{fetrat2024manatts,
      title={ManaTTS Persian: A Recipe for Creating TTS Datasets for Lower-Resource Languages}, 
      author={Mahta Fetrat Qharabagh and Zahra Dehghanian and Hamid R. Rabiee},
      journal={arXiv preprint arXiv:2409.07259},
      year={2024},
}
```

---
