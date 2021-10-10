# Kaggle Digit Recognition with 100% 
![](https://i.imgur.com/vcCYYYE.png)

# Pretrained
[Donwload here](https://drive.google.com/file/d/16OSYlP60_lSTEZQfVLTNpHI91VIY9an4/view?usp=sharing)

# My ideas:
* Combine MNIST dataset with Kaggle Dataset
* Using Data Augmentation for more data
* Create a simple neural network which outputs 512-d vector, with ArcFace softmax 
* After training, I use that trained model (512-d) to encode images
* Using training data as images in database
* Then I perform similarity searching to predict test images


# Preferences
[ArcFace: Additive Angular Margin Loss for Deep Face Recognition,Deng, Jiankang and Guo, Jia and Niannan, Xue and Zafeiriou, Stefanos.](https://arxiv.org/abs/1801.07698)

