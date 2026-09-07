# Human-in-the-Loop-Active-Learning-for-Reducing-Annotation-Cost-in-Medical-Image-Classification
BRACU ML Project for CSE427 


Abstract		




It is very expensive to get reliable medical-image labels, as those typically will need to be reviewed by experts. Rather than annotating each of the images, this study explores the possibility of a smaller subset of images that is sufficient to compete in chest X-ray classification with an active-learning system. The numbers of the training images and independent test images after duplicate removal were 5,206 and 624, respectively. The performance of the original CNN, DenseNet-121 and ResNet50 models were first compared with a fixed validation split. To select the best feature extractor to be used in the activelearning stage, ResNet-50 was used for validation with the highest balanced accuracy of 0.9697 was chosen.
Three acquisition strategies compared against a stratified 5% labeled pool of 221 images at labeling budgets varying from 5% to 40% are: Random sampling, Entropy sampling, and a Hybrid uncertainty–diversity method. For each of three stochastic runs, Entropy and Hybrid achieved or matched the 100%-label reference F1-score of 0.9097 with approximately 10% of the training pool; Random first surpassed the reference around 30%. However, although Hybrid had the highest normalized area under the mean-F1 learning curve, 0.9137, the difference was also small compared to Entropy. From these result, it is found that model guided sample selection can help to minimize the number of annotations from this task. The estimated saving, however, relies on the dataset, cold start pool and fixed feature representation.



