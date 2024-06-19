---

This document provides an overview of each code file in our project, facilitating easier navigation and understanding.

### AmharicBrailleRecognitionModelTrain:
This is the core project file where we
- Train the Amharic Braille recognition model.
- Save the trained model.
- Provide new data to the model for prediction.
- Essentially, all key operations are handled in this file.

### BrailleAugmentation:
This code file focuses on augmenting the dataset. Here, we
- Enhance the original dataset images by adjusting brightness and darkness for more diverse training.
- Shift the images by 9 degrees multiple times.
- Rotate the images by 9 degrees multiple times.

### ImageCrop:
This part of the code processes the training dataset to
- Crop each image to dimensions of (96x170).
- Convert images to grayscale, turning them into black and white based on a threshold value of 128.

### AmharicBrailleLoadModels:
This file contains our most accurate model for easy demonstration without retraining. Note:
- The showcase works only on our local PC as the model is saved locally.
- You can achieve the same results by saving the model you train in the `AmharicBrailleRecognitionModelTrain` file.

### AmharicBrailleChartPrepare:
This code is used to print the same pattern multiple times, preparing the physical chart that we manually printed and colored.

---
