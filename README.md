# Covid19-Intrepreter
The COVID-19 pandemic in 2020 caused a global shortage of testing
kits, and it also increased new cases and fatalities. Predicting disease severity early is crucial to preventing fatalities, maximizing hospital resources,
and aiding clinicians’ decisions. In this study, we investigate the effectiveness of ensemble learning strategies in image classification tasks with pretrained Convolutional Neural Network (CNN) models. The rapid growth of deep learning has resulted in the emergence of pre-trained CNN architectures such as VGG, ResNet, and DenseNet, which score exceptionally well on different image recognition benchmarks. However, relying on a single model may not necessarily reflect the entire complexity of the underlying data distribution. Ensemble learning, which combines the predictions of numerous models, is a potential strategy for improving predictive performance. We ran trials using three commonly used pre-trained CNN models: VGG, ResNet, and DenseNet, which were trained on a dataset of images from three classes. The dataset was used to 
fine-tune each model, and their performance was evaluated on a separate test. Furthermore, we studied decision-level fusion strategies for aggregating predictions from these models, resulting in an ensemble model. Our evaluation measures comprised classification precision, recall, accuracy and F1 score, as well as confusion
matrices. The results show that, while individual pre-trained CNN models are highly accurate, ensemble learning techniques can improve predictive
performance even further. The ensemble model outperformed individual models, demonstrating higher accuracy and robustness in picture classification tests. This paper sheds light on the efficacy of ensemble learning using pre-trained CNN models and demonstrates its potential for increasing classification performance in a variety of real-world applications, including medical diagnosis, object recognition, and remote sensing.The experimental results suggest that the proposed fusion method is effective, with better classification accuracy when compared to separate models. This study provides useful insights on using deep learning models and fusion procedures to improve image classification performance. Future research directions include looking into more advanced ensemble approaches and the transferability of models across domains.
Keywords: Image classification, pre-trained models, deep learning,ensemble learning, decision-level fusion, convolutional neural networks (CNNs), data augmentation, computer vision.

Tools: Python, Jupyter Notebook, Tensorflow, Keras, Matplotlib
