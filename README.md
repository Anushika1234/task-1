This script visualizes the activation maps from convolutional layers in a pre-trained CNN model to understand which image regions are activated for age detection.

1-Model Loading: The pre-trained model (Age_Sex_Detection.keras) is loaded, and its summary is displayed.

2-Image Preprocessing: The image is loaded, resized, and normalized to match the input format expected by the model.

3-Extracting Activations: A sub-model is created to extract the outputs from the convolutional layers of the CNN.

4-Visualizing Activation Maps: Activation maps from the first few convolutional layers are visualized. Each filter's activation is normalized and displayed using matplotlib.
