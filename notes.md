# Notes

## Zero Shot Classification
- Zero-shot classification is a machine learning and AI technique that allows a model to classify data into categories it has never explicitly been trained on.
- In traditional machin learning techniques, learning is done using one-hot encoding. For Example, if you train a model to output dog, cat, or car, the model views these categories as discrete, isolated boxes.(one-hot encoding).
- However, in this project instead if this we use semantic space embeddings. Instead of teaching the model to map EEG signals to a rigid label, we teach it to map EEG signals into a map of concepts—a continuous vector space where words or images with similar meanings sit close to each other.
-  Think of CLIP space as a massive, multi-dimensional universe of concepts where: Dog and Cat are floating close together because they are both "animals," "pets," and "furry." Even though the model has never seen an EEG scan of someone looking at an aircraft carrier, the text "aircraft carrier" already has a fixed coordinate in this universe.

<img width="647" height="186" alt="Screenshot 2026-06-28 at 4 33 11 PM" src="https://github.com/user-attachments/assets/d1aff17f-fd86-496e-a5b3-3817f0f76f48" />

## Unsupervised Learning
- Unsupervised learning is a type of machine learning that analyzes and clusters unlabeled datasets. Instead of relying on predefined answers or human guidance, the algorithm discovers hidden patterns, structures, or underlying relationships in the input data on its own

Dataset Used: Things-EEG
<br>Paper: Bridging the Vision-Brain Gap with an Uncertainty-Aware Blur Prior},
<br>Author = Wu, Haitao and Li, Qing and Zhang, Changqing and He, Zhen and Ying, Xiaomin
