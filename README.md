This project demonstrates how to perform inference on a pre-trained ResNet-18 model using TensorRT. The process involves:

- **Model Loading:** A ResNet-18 model is loaded and optimized for inference using TensorRT.
- **Input Preprocessing:** Input images are preprocessed (resize, normalize, etc.) to match the expected format.
- **TensorRT Inference:** The preprocessed input is transferred to the GPU, and the model performs inference to predict the class of the image.
- **Memory Management:** Proper memory allocation and deallocation on the GPU using PyCUDA are ensured to avoid memory issues during inference.
- **Class Mapping:** The inference output is mapped to the corresponding class label using ImageNet class labels.
