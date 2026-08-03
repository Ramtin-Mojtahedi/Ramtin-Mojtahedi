<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ramtin-Mojtahedi/Ramtin-Mojtahedi/main/assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ramtin-Mojtahedi/Ramtin-Mojtahedi/main/assets/banner-light.svg">
  <img width="100%" alt="Ramtin Mojtahedi — Postdoctoral Medical AI Researcher" src="https://raw.githubusercontent.com/Ramtin-Mojtahedi/Ramtin-Mojtahedi/main/assets/banner-light.svg">
</picture>

<div align="center">
  <br>
  <a href="https://ramtin-mojtahedi.github.io/"><img src="https://img.shields.io/badge/Portfolio-173E30?style=for-the-badge&amp;logo=githubpages&amp;logoColor=white" alt="Portfolio"></a>
  <a href="https://scholar.google.com/citations?user=KjUrlGUAAAAJ&amp;hl=en"><img src="https://img.shields.io/badge/Google_Scholar-6377CF?style=for-the-badge&amp;logo=googlescholar&amp;logoColor=white" alt="Google Scholar"></a>
  <a href="https://orcid.org/0000-0002-3953-3256"><img src="https://img.shields.io/badge/ORCID-7CAB38?style=for-the-badge&amp;logo=orcid&amp;logoColor=white" alt="ORCID"></a>
  <a href="https://www.linkedin.com/in/ramtin-mojtahedi/"><img src="https://img.shields.io/badge/LinkedIn-315E9B?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn"></a>
</div>

## About

I am a **Postdoctoral Medical AI Researcher** at **Toronto General Hospital, University Health Network, and the University of Toronto**, with a Ph.D. in Computing from Queen's University. I develop clinically grounded machine-learning research across medical imaging, multimodal prediction, and trustworthy evaluation.

My current work focuses on multimodal forecasting of lung-transplant outcomes. My broader research spans liver and abdominal tumour segmentation, foundation-model adaptation, parameter-efficient and few-shot learning, self-supervised representation learning, radiomics, and interpretable clinical prediction.

> The repositories below include research-code snapshots, experimental notebooks, and publication companions. Each repository README is the source of truth for its data, reproducibility, licensing, and intended-use status.

## Research focus

| | Area | Selected themes |
|:--:|---|---|
| 🩻 | **Medical image computing** | 2D/3D segmentation, CT and ultrasound analysis, tumour classification, radiomics |
| 🧠 | **Foundation & vision models** | SAM/MedSAM, Swin UNETR, Vision Transformers, CNN–transformer hybrids |
| ⚡ | **Data-efficient learning** | LoRA, PEFT, few-shot, transfer, self-supervised and contrastive learning |
| 🧬 | **Multimodal clinical modelling** | Imaging–clinical fusion, longitudinal prediction, survival and risk modelling |
| 🛡️ | **Trustworthy evaluation** | Calibration, uncertainty, interpretability, domain shift and external validation |
| 🔬 | **Research engineering** | Experiment design, cross-validation, scientific visualization and reproducible workflows |

## Technical toolkit

<div align="center">
  <img src="https://img.shields.io/badge/Python-173E30?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&amp;logo=pytorch&amp;logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/MONAI-315E9B?style=flat-square" alt="MONAI">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&amp;logo=tensorflow&amp;logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&amp;logo=keras&amp;logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&amp;logo=huggingface&amp;logoColor=111111" alt="Hugging Face">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&amp;logo=scikitlearn&amp;logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&amp;logo=jupyter&amp;logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/NumPy-315E9B?style=flat-square&amp;logo=numpy&amp;logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/pandas-173E30?style=flat-square&amp;logo=pandas&amp;logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/XGBoost-6377CF?style=flat-square" alt="XGBoost">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&amp;logo=opencv&amp;logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&amp;logo=git&amp;logoColor=white" alt="Git">
</div>

## Featured research

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ramtin-Mojtahedi/peft-sam-liver-ct">PEFT for SAM in liver CT</a></h3>
      <p>Research companion for parameter-efficient adaptation of SAM/MedSAM-style foundation models to liver-tumour segmentation in CT.</p>
      <p><code>PyTorch</code> · <code>MONAI</code> · <code>PEFT</code> · <code>Foundation models</code></p>
      <p><a href="https://doi.org/10.1117/12.3087835">Paper / DOI →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ramtin-Mojtahedi/PEFT-FSL-MViT-LTS">PEFT + few-shot liver segmentation</a></h3>
      <p>LoRA and few-shot learning experiments with Swin UNETR for liver-tumour segmentation in CT.</p>
      <p><code>LoRA</code> · <code>Few-shot learning</code> · <code>Swin UNETR</code></p>
      <p><a href="https://doi.org/10.1117/12.3046253">Paper / DOI →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ramtin-Mojtahedi/SimSiam-LiverCancer-CL">SimSiam liver-cancer classification</a></h3>
      <p>Self-supervised SimSiam pretraining for three-class classification of primary and secondary liver cancers from CT-derived tumour images.</p>
      <p><code>TensorFlow</code> · <code>SimSiam</code> · <code>Self-supervised learning</code></p>
      <p><a href="https://doi.org/10.1007/978-3-031-47425-5_28">Paper / DOI →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ramtin-Mojtahedi/AI-Radiomics-Carotid">AI radiomics for carotid imaging</a></h3>
      <p>Analysis notebooks comparing clinical-history, vascular-ultrasound, and carotid-plaque radiomic features for cardiovascular-risk prediction.</p>
      <p><code>Radiomics</code> · <code>scikit-learn</code> · <code>XGBoost</code></p>
      <p><a href="https://doi.org/10.1016/j.ultrasmedbio.2026.05.006">Paper / DOI →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ramtin-Mojtahedi/OVTPS">Optimal ViT patch size</a></h3>
      <p>Publication companion for research on selecting a Vision Transformer patch size for liver-tumour segmentation.</p>
      <p><code>Vision Transformers</code> · <code>Segmentation</code> · <code>CT</code></p>
      <p><a href="https://doi.org/10.1007/978-3-031-18814-5_11">Paper / DOI →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Ramtin-Mojtahedi/Ramtin-Mojtahedi.github.io">Professional research portfolio</a></h3>
      <p>A structured scholarly portfolio with publication feeds, machine-readable metadata, responsive presentation, and accessibility-conscious interaction.</p>
      <p><code>Jekyll</code> · <code>HTML/CSS</code> · <code>JavaScript</code> · <code>JSON-LD</code></p>
      <p><a href="https://ramtin-mojtahedi.github.io/">Visit the portfolio →</a></p>
    </td>
  </tr>
</table>

<details>
  <summary><strong>Browse the complete existing project archive</strong></summary>

  <br>

- [AI-Radiomics-Carotid](https://github.com/Ramtin-Mojtahedi/AI-Radiomics-Carotid)
- [Assignment-2---AIDI1012](https://github.com/Ramtin-Mojtahedi/Assignment-2---AIDI1012)
- [Assignment-4---Sentiment-Analysis](https://github.com/Ramtin-Mojtahedi/Assignment-4---Sentiment-Analysis)
- [BRATS_OVTPS](https://github.com/Ramtin-Mojtahedi/BRATS_OVTPS)
- [Central_Line_Challenge](https://github.com/Ramtin-Mojtahedi/Central_Line_Challenge)
- [Code-Deep-dive](https://github.com/Ramtin-Mojtahedi/Code-Deep-dive)
- [gazebo_models](https://github.com/Ramtin-Mojtahedi/gazebo_models)
- [Group_Share_Implementation](https://github.com/Ramtin-Mojtahedi/Group_Share_Implementation)
- [Intuition-Report-1](https://github.com/Ramtin-Mojtahedi/Intuition-Report-1)
- [Intuition-Report-2](https://github.com/Ramtin-Mojtahedi/Intuition-Report-2)
- [Intuition_Report_3](https://github.com/Ramtin-Mojtahedi/Intuition_Report_3)
- [Intuition_Report_4](https://github.com/Ramtin-Mojtahedi/Intuition_Report_4)
- [intuition_Report_6](https://github.com/Ramtin-Mojtahedi/intuition_Report_6)
- [Intuition_Report_7](https://github.com/Ramtin-Mojtahedi/Intuition_Report_7)
- [Intuition_Report_8](https://github.com/Ramtin-Mojtahedi/Intuition_Report_8)
- [Intuition_Report_9](https://github.com/Ramtin-Mojtahedi/Intuition_Report_9)
- [Liver_Tumour_Recognition_and_Classification_with_Model-agnostic_Interpretable_Explanations](https://github.com/Ramtin-Mojtahedi/Liver_Tumour_Recognition_and_Classification_with_Model-agnostic_Interpretable_Explanations)
- [Optimal-Vision-Transformer-Patch-Size](https://github.com/Ramtin-Mojtahedi/Optimal-Vision-Transformer-Patch-Size)
- [OVTPS](https://github.com/Ramtin-Mojtahedi/OVTPS)
- [PEFT-FSL-MViT-LTS](https://github.com/Ramtin-Mojtahedi/PEFT-FSL-MViT-LTS)
- [peft-sam-liver-ct](https://github.com/Ramtin-Mojtahedi/peft-sam-liver-ct)
- [Ramtin-Mojtahedi.github.io](https://github.com/Ramtin-Mojtahedi/Ramtin-Mojtahedi.github.io)
- [research-contributions](https://github.com/Ramtin-Mojtahedi/research-contributions)
- [SimSiam-LiverCancer-CL](https://github.com/Ramtin-Mojtahedi/SimSiam-LiverCancer-CL)
- [UNETR](https://github.com/Ramtin-Mojtahedi/UNETR)

</details>

## Professional snapshot

| **18** | **9** | **26** | **900+** | **28** | **10** |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Scholarly works | Presentations | Honours & distinctions | Students taught or supported | Leadership & volunteer roles | Programming languages |

<p align="center"><sub>See the <a href="https://ramtin-mojtahedi.github.io/">sourced portfolio</a> for the complete record and context.</sub></p>

---

<div align="center">
  <strong>Research, publications, and contact</strong><br><br>
  <a href="https://ramtin-mojtahedi.github.io/research/">Research</a> ·
  <a href="https://ramtin-mojtahedi.github.io/publications/">Publications</a> ·
  <a href="https://ramtin-mojtahedi.github.io/#contact">Contact</a>
</div>
