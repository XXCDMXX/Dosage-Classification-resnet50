# Dosage-Classification-resnet50
Classification based on the medicine dosage forms. There are 5 categories: monochrome capsule, bicolor capsule, oval pill, cod liver oil, round pill. This model is derived from fine-tuning the fully connected layer of ResNet50.

Fine-tuning the fully connected layer (output layer) of ResNet50 in Colab, splitting the original dataset of 667 images into 80% training set and 20% validation set, and finally testing on 50 images in the test set.

Chinese: 在colab微调resnet50的全连接层(输出层), 把667张原始数据集划分为80%的训练集和20%的验证集, 最后在50张测试集进行测试.

Reference: [Github](https://github.com/TommyZihao/Train_Custom_Dataset/图像分类).