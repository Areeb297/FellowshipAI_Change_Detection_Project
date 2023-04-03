## Fellowship completion certification at Fellowship.AI

![image](https://user-images.githubusercontent.com/51030860/229514342-3fd4b9cb-953e-45aa-b0c0-2929d0d8c6b6.png)


## Developing Siamese Networks with Pre-trained Models

The code contained in this repository demonstrates the creation of Siamese Networks in PyTorch by leveraging pre-trained models, enabling the training process to utilize bi-temporal images and produce change masks that are beneficial for disaster detection. The LEVIR-CD Dataset, a large-scale remote sensing building Change Detection dataset, is employed for this purpose. This newly introduced dataset serves as a benchmark for assessing change detection (CD) algorithms, particularly those founded on deep learning techniques.

Implemented a pre-trained Siamese Network using Convolutional Neural Networks, Attention mechanism, Transformers and more, called ![SarasNET](https://github.com/f64051041/SARAS-Net) to apply on satellite imagery data to develop a change detection model. The SarasNET is fine-tuned on different datasets such as CDD dataset to output relevant change masks.

### Entirely Unsupervised Approach for Change detection:

The model is trained to output a similarity score between two images without using any ground truth image masks. We use Siamese Networks for this & this model may prove to be useful in an alert system where if a higher than normal similarity is output from the model given two bi-temporal images of the same location, then it may be worth for the inspectors or the land authorities to take action.

Below are tensorboard screenshots from the training process:

![image](https://user-images.githubusercontent.com/51030860/228424922-9c59f2bd-cf81-48e7-b4bf-45b4bb9d8d46.png)
![image](https://user-images.githubusercontent.com/51030860/228424949-a1e3b1f5-98ee-46b4-aa2f-d0838baec058.png)
![image](https://user-images.githubusercontent.com/51030860/228424965-dbc6e32a-a72b-483f-9f6f-cba79209e7c0.png)
