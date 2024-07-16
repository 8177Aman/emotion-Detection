# Emotion Detection Using CNN and FER-2013 Dataset

## Tech Stack
- Python
- TensorFlow
- Keras
- ResNet50v2
- VGG16
- OpenCV

## Description
This project uses Convolutional Neural Networks (CNN) and the FER-2013 dataset to focus on emotion detection. The primary objectives and achievements of the project are:

- **Addressed class imbalance**: Employed image augmentation and class weights to improve model robustness and handle class imbalance in the FER-2013 dataset.
- **Custom CNN models**: Designed and iterated on custom CNN models, including advanced architectures such as VGG16 and ResNet50v2, to optimize performance.
- **Accuracy**: Achieved a 66% overall accuracy on emotion classification. Based on ResNet50v2, the final model provided detailed precision, recall, and F1-scores across 7 emotion labels.
- **Real-time detection**: Deployed the model for real-time emotion detection in live video streams using Gradio and OpenCV, showcasing emotion labels dynamically on-screen.
- **Comprehensive documentation**: Authored a comprehensive blog detailing the project's approach, challenges, and resolutions, and shared the source code on GitHub for community engagement.

## Installation
To run this project on Google Colab, follow these steps:

1. Open the Google Colab notebook link: [Emotion Detection Colab Notebook](https://colab.research.google.com/drive/1MtESvQG56lwG3bgPvk3Z-qFQ26APiXKc#scrollTo=bN2nKBng5TFR)
2. Follow the instructions within the notebook to run the cells sequentially.
3. Ensure you have the FER-2013 dataset available, or use the provided link within the notebook to download it.

## Usage
1. Open the Colab notebook and run the cells in sequence.
2. The notebook will guide you through the steps of data preprocessing, model training, and real-time emotion detection.
3. The final part of the notebook demonstrates real-time emotion detection using Gradio and OpenCV.

## Contributing
Contributions are welcome! Here's how you can contribute to the project:

1. Fork the repository.
2. Create your feature branch:
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/AmazingFeature
    ```
5. Open a pull request.
