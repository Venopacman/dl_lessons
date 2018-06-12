# 1st lab - hotdog\not hotdog classification on ImageNet data

There are several classifiers:
- classic SVM and RandomForest -- about 0.8 accuracy on validation set
- 3-layer CNN with relu activation -- about 0.85 accuracy on validation set
- pre-trained VGG16 features + linear SVM -- about 0.95 accuracy on validation set
- fine-tuned VGG16 + linear SVM -- small boost

