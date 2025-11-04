ABSTRACT
Breast cancer detection from mammography images is challenging due to limited
annotated datasets and, along with the high similarity between classes, leads to deep
learning models overfitting. This study explored Prototypical Contrastive Learning
(PCL), a self-supervised learning approach, to address these challenges by learning
meaningful representations with minimal reliance on labels. The original PCL framework
was adapted for mammography by enabling single-GPU training, integrating multiple
backbones (ResNet-34, ResNet-50, MobileNet, and DenseNet-121), and handling
greyscale images. Both the original and cropped datasets were used to assess the effect of
removing irrelevant background, while more experiments were run with varying batch
sizes, learning rates, and temperature parameters. Results showed consistent
improvements with cropping and hyperparameter tuning. DenseNet-121 achieved the best
performance, with 92.3% accuracy, 92.5% precision, and 96.2% specificity, while
MobileNet provided competitive results with 66.7% accuracy and 69.6% precision on the
cropped dataset. The findings shed a light onto PCL framework's potential as a viable
complement to supervised methods in low-data medical imaging tasks.
