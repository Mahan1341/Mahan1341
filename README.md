

Machine Learning & AI student at **Innopolis University**, studying **Mathematical Foundations of Artificial Intelligence**.

I build practical ML/CV/NLP systems, work with deep learning pipelines, and contribute to existing open-source codebases.

## Projects

### [Semantic Image Segmentation](https://github.com/Mahan1341/Image-segmentation-hackathon)
Solo hackathon project for **3-class semantic segmentation of 6-band multispectral GeoTIFF imagery** using **DeepLabV3+** with an **EfficientNet-B5** encoder in PyTorch. The reconstructed reproducible pipeline includes GeoTIFF-based dataset recovery, training-split band normalization, Albumentations augmentation, Dice + class-weighted CrossEntropy loss, per-class IoU evaluation, checkpointing, and prediction visualization. Best mean foreground IoU on the verified recovered validation subset: **0.621**.

### [Tatar Text Detoxification](https://github.com/Mahan1341/tatar-text-detoxification)
Solo low-resource NLP project developed for **ИИ-ЗАМАН Хак 2025**. Built **200,000 synthetic toxic → clean training pairs** from a Tatar news corpus and fine-tuned **mT5-small** for sequence-to-sequence detoxification. The project also includes lexical and **Tatar2Vec + XGBoost** baselines, hybrid inference, retrospective evaluation on **600 human-written Tatar references**, reusable CLI tools, tests, and CI.

### [Smart Intercom Face Unlock](https://github.com/Mahan1341/smart-intercom-face-unlock)
End-to-end computer vision system that recognizes an authorized user in an Android intercom app and triggers the door action when no public API is available. Uses a **pretrained ArcFace ONNX model**, OpenCV, cosine similarity, template matching, screen capture, and UI automation.

## Open Source

Merged contributions to existing open-source codebases:

- [objectionary/lints](https://github.com/objectionary/lints) — Java static-analysis tooling for EO/XMIR
- [objectionary/eoc](https://github.com/objectionary/eoc) — JavaScript/Java command-line tooling for the EO ecosystem

Work included dependency/build fixes, test infrastructure changes, regression tests, and command behavior fixes.

## Tech Stack

**Languages:** Python, Java, JavaScript  
**ML / Data:** PyTorch, Transformers, Hugging Face Datasets, scikit-learn, XGBoost, NumPy, Pandas  
**Computer Vision:** OpenCV, ONNX Runtime, Albumentations  
**Tools:** Git, GitHub, Jupyter Notebook

## Education

**Innopolis University**  
Mathematical Foundations of Artificial Intelligence
