# PaliGemma with PyTorch: Training and Inference

A practical notebook-based exploration of **PaliGemma**, a vision-language model that connects image understanding with language generation. The repository focuses on the training/adaptation and inference workflow, using the **Flickr8k image-captioning dataset** as its project context.

The notebook is intended as a code-oriented learning resource for understanding multimodal AI workflows in PyTorch.

## Project overview

PaliGemma combines visual and language capabilities so that image content can be processed in a language-modeling context. Image captioning is a natural way to study this interaction: the model receives an image and generates a text description.

This project brings together the key ideas behind:
- Visual and textual inputs in a vision-language workflow
- Image-caption pairs and dataset preparation
- Multimodal representation and visual-language alignment
- Model training or adaptation workflow
- Inference and generated text outputs

## Dataset: Flickr8k

The notebook filename identifies **Flickr8k** as the dataset used in this project. Flickr8k is commonly used for image-captioning experiments and pairs images with natural-language descriptions.

The dataset provides a practical setting for exploring how a vision-language model can connect visual content to descriptive text. Refer to the notebook for the exact download, preprocessing, split, and data-loader implementation.

## Notebook

**[Open the PaliGemma training and inference notebook](https://github.com/AliHassanAbbas/PaliGemma-training-inference-pytorch/blob/main/PaliGemma_from_scratch_Flickr8k_%282%29%20%281%29.ipynb)**

Open the notebook in Jupyter or Google Colab. Before running it, review the setup cells for package versions, model access requirements, dataset paths, checkpoint/weight configuration, and available GPU memory.

## Concepts and technical skills

- **Vision-language modelling:** connecting image inputs with natural-language outputs
- **Multimodal learning:** working with visual and text modalities in one model workflow
- **Image captioning:** generating descriptive language conditioned on an image
- **Dataset preparation:** working with image-caption pairs and the Flickr8k dataset
- **PyTorch model workflow:** understanding training/adaptation and inference stages
- **Model evaluation and experimentation:** inspect the notebook for the exact metrics and evaluation procedure used

**Technical topics:** PyTorch · PaliGemma · Vision-language models (VLMs) · Multimodal AI · Image captioning · Flickr8k · Image-text pairs · Visual representation learning · Language generation · Model training and inference

## Scope and implementation note

This is a practical study of PaliGemma's training/adaptation and inference workflow. The repository should not be interpreted as claiming that the original PaliGemma foundation model was pretrained from random initialization. The exact degree of model adaptation, trainable components, pretrained assets, hyperparameters, evaluation metrics, and compute requirements are defined by the notebook; please consult it before drawing conclusions about training scope or results.

Use model assets according to their respective access terms and licenses.

## Author

**Ali Hassan Abbas** — AI Researcher, PyTorch Specialist, and AI Educator.

- [GitHub](https://github.com/AliHassanAbbas)
- [LinkedIn](https://www.linkedin.com/in/alihassanofficial/)
- [YouTube — Mrelan](https://www.youtube.com/@mrelanofficial)
- [Portfolio](https://alihassanabbas.github.io)

---

*Understand how images and language meet in a multimodal model—then study the training and inference workflow hands-on.*
