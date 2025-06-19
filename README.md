# AI Learning Network for the Assessment of Lung Inflammation 

Submitted for publication.

Densely Connected Convolutional Networks, DenseNet (1), was employed for image analysis and development of the learning model. DenseNet, which combines any layer to all subsequent layers (such that the output layer receives inputs from the features of all previous levels), is composed of convolutional layers, pooling, batch normalization, activation function, transition layers, dense blocks, and a classification layer. 
Hematoxylin and eosin (H&E) stained slides (scanned at 40x) were manually annotated by a pulmonary pathologist for two classes. The first class was inflammation, and the second class was background (no inflammatory cells). The algorithm was trained and evaluated for classification with a resolution value of 2 μm/pixel.
The cross-entropy rates were 0.006 for 4480 +/- 80 iterations, and the DenseNet classification F1 scores were overall 0.920 (95% CI 0.915 – 0.925), inflammation 0.875 (95% CI 0.868 – 0.881) and background 0.965 (95% CI 0.969 – 0.962). 

Reference:
1.	Huang G., Liu Z., Van Der Maaten L., Weinberger K.Q. Densely connected convolutional networks. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. July 2017; pp. 4700–4708. 

![R8-15_a](https://github.com/user-attachments/assets/d3e332ee-1afb-4208-a27e-34b0089e1baa)
![R8-20_d](https://github.com/user-attachments/assets/ebc4c7ed-92f3-4526-96a4-970d3d30ba43)
![R8-15_c - Copyb](https://github.com/user-attachments/assets/af840091-b072-4c2d-a225-7cd373c9941c)
