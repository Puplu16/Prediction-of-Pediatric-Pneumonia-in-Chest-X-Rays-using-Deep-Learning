# Prediction-of-Pediatric-Pneumonia-in-Chest-X-Rays-using-Deep-Learning
This project develops a deep learning model to automatically detect pediatric pneumonia from chest X-rays. Using CNNs like ResNet and DenseNet, it classifies images to support rapid diagnosis in low-resource settings. The pipeline includes preprocessing, model training, and Grad-CAM heatmaps for interpretable results.

Pneumonia remains a leading cause of child mortality globally, with its impact most severe in low-resource settings where radiological expertise is scarce. This project develops an automated deep learning system to enable rapid and accurate diagnosis of pediatric pneumonia from chest X-ray images, addressing a critical gap in healthcare delivery.

The solution leverages advanced Convolutional Neural Networks (CNNs), including architectures like ResNet, DenseNet, and VGG, which are adept at learning intricate patterns in medical imagery. Through transfer learning, these pre-trained models are fine-tuned to classify X-rays as either normal or indicative of pneumonia.

The end-to-end pipeline encompasses several stages: preprocessing steps like image normalization, augmentation, and resizing to standardize the input data; model development and training to optimize diagnostic performance; and rigorous evaluation using metrics such as accuracy, precision, recall, and F1-score. To ensure transparency and build clinical trust, the project employs Grad-CAM visualization techniques, generating heatmaps that highlight the regions of the lung most influential in the model’s decision.

By providing a fast, reliable, and AI-assisted diagnostic tool, this project demonstrates the potential to support healthcare workers in under-resourced areas, ultimately contributing to reduced diagnosis times and improved patient outcomes.
