# Image Captioning System

This project aims to create an Image Captioning System capable of generating descriptive captions for images and videos. The system utilizes deep learning models to analyze the content of images and generate relevant textual descriptions.

### Overview
The Image Captioning System employs a combination of deep learning techniques, including Xceptionnet for image feature extraction and LSTM for caption generation. By training on the MSCOCO dataset, the system achieves significant accuracy in generating captions for a variety of images.

### Project Details
- **Objective**: To develop an Image Captioning System capable of generating descriptive captions for images and videos.
- **Models Implemented**:
  - Xceptionnet for image feature extraction.
  - LSTM for predicting the next word in the caption.
- **Evaluation Metrics**: BLEU-4 scores are used for evaluating the performance of the system.
- **Key Contributions**:
  - Achieved BLEU-4 score of 34.6 on MSCOCO dataset.
  - Implemented Faster RCNN to improve BLEU-4 score to 37.3 without changing the architecture/loss function.

### Dataset
The system is trained on the MSCOCO dataset, which contains a large collection of images with corresponding textual descriptions.

### Files
1. **Image_Captioning_Final_Evaluation.ipynb**: This notebook contains the implementation of the Image Captioning System, including data preprocessing, model training, and evaluation.
2. **Image_Captioning_Testing_Code_Final_Evaluation.ipynb**: This notebook provides testing code for evaluating the trained model on images and videos.
3. **tokenizer.p**: Pickle file containing the tokenizer used for text vectorization.
4. **model_final.h5**: Pretrained model file used for testing the Image Captioning System. (Download: https://drive.google.com/file/d/1-vQFkGLO_h33noH9xiiOV3eNYO3BXT4Q/view?usp=drive_link)

### Usage
1. Clone the repository and navigate to the project directory.
2. Run the provided Jupyter notebooks to train and test the Image Captioning System.
3. Update the file paths in the code for proper functioning.
4. Use the provided pretrained model file for testing the system.

### References
- Original paper on Image Captioning System.
- MSCOCO dataset: (https://cocodataset.org/#home)
- Xceptionnet: (https://arxiv.org/abs/1610.02357)
- LSTM: (https://www.bioinf.jku.at/publications/older/2604.pdf)

### License
This project is licensed under the [MIT License](LICENSE).
