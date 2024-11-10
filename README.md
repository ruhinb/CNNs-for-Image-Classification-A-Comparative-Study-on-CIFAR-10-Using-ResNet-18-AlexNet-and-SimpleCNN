In this study, I have explored the performance of dif-
ferent Convolutional Neural Network (CNN) architectures
for image classification using the CIFAR-10 dataset, a well-
known benchmark in computer vision consisting of 60,000
images across 10 classes. I have implemented and rigor-
ously compared three architectures: ResNet-18, AlexNet,
and a custom-designed SimpleCNN. Each model has been
trained from scratch, and I have applied a refined hyper-
parameter tuning process to ResNet-18. This involves opti-
mizing learning rates, batch sizes, and selecting between
the SGD and Adam optimizers. I have used techniques
such as early stopping and learning rate scheduling to en-
hance model performance and prevent overfitting. My re-
sults show that ResNet-18 outperforms the other models,
achieving a validation accuracy of 80.4% and a final test
accuracy of 80.5%, demonstrating its robustness and gen-
eralization capabilities. AlexNet and SimpleCNN, while
simpler, provide insights into the trade-offs between model
complexity and performance, achieving test accuracies of
71.6% and 72.5%, respectively. I have presented a detailed
analysis of performance metrics, including accuracy and
loss curves. These findings underscore the importance of
hyperparameter selection and architectural choices in deep
learning models.
