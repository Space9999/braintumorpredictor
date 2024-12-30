# braintumorpredictor
Based on brain CT and MRI scans, a ML model to predict presence or absence of brain tumor

Hints 
- need training, test and validation datasets
- need to standardize images first. Cursorily looking at images shows me some are zoomed, some are off center, contrast levels are different, etc
- use image-based prediction ML methods -> convolutional neural nets -> can add/layer different techniques with this
- keras models
- someone got 94% accuracy in prediction already on kaggle couple days ago. Goal is to either get that or beat it.

Data from xyz doctor from xyz university
2300 healthy brain CT scans
2000 healthy brain MRI scans
2318 tumorous brain CT scans
3000 tumorous brain MRI scans
https://www.kaggle.com/datasets/murtozalikhon/brain-tumor-multimodal-image-ct-and-mri/data
