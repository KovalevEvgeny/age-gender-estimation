# Age estimation and gender classification

In this project, I solved two tasks: given a photo, estimate age and gender of a person. Two different neural networks have been created and trained - the first by scratch, and the second via fine-tuning. Both neural networks have branch-like structure, which means that they can run training and inference for both tasks simultaneously.

Instruments used: keras, albumentations.

* [`age_gender_estimation.ipynb`](https://nbviewer.org/github/KovalevEvgeny/age-gender-estimation/blob/main/age_gender_estimation.ipynb) - general project file
* [`model_inference.ipynb`](https://nbviewer.org/github/KovalevEvgeny/age-gender-estimation/blob/main/model_inference.ipynb) - file which shows how to perform model inference
