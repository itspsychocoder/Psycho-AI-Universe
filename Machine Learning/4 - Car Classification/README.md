# Car Classifiction
This project implements a Convolutional Neural Network (CNN) to classify images of cars into different categories based on the car brand (e.g., Audi, Rolls Royce). The model is built using TensorFlow and Keras.

## Dataset
The dataset consists of two folders:

- train/: Contains subfolders for each car type with images of the respective cars.
- test/: Contains subfolders with test images of the respective car types for evaluation.

Each subfolder in both the train/ and test/ directories corresponds to a car brand (e.g., Audi, Rolls Royce) and contains images of that brand.


## Results
- Test Accuracy: 70% (Baseline without fine-tuning)
- Potential Improvements: Fine-tuning VGG16, experimenting with optimizers, more data augmentation.

## Future Work
- Improve accuracy using more advanced techniques like fine-tuning, increasing image resolution, or trying different pre-trained models (ResNet, Inception).
- Expand dataset to include more car brands.
- Build a user interface to upload and classify car images.
