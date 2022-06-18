# REUSEIT
This app aims to reduce the amount of waste produced at first place and even if waste is generated, ways to reuse it/dispose it properly will be given. 

The world generates at least 3.5 million tons of waste per day and this number is still increasing day by day that's why we need to aware about waste.
This web application can classify waste with 9 different waste materials and it will show you the details of that particular waste materials. This will help to raise awareness for people to reduce and recycle waste.

# Overview
There are LIGHT BLUBS, PAPER, PLASTIC, ORGANIC, GLASS, BATTERIES, CLOTHES, METAL, E-WASTE total 9 different types of waste materials which are use for recycling.
In this project i have collected and filtered data by my self from google images and dreamstime.com
Here i have 8369 images belonging 9 classes.
Here i have trained dataset using VGG16 Transfer Learning technique of CNN for classification.
Here i have trained this model till 28 epochs and i got 69.77% accuracy.
Initially i had trained my model with Inceptionv3 and it's gave me 90.34% accuracy. But it was not accurate when i tested it on some images. But when i tested VGG16 with 69.77% accuracy it gives me accurate result.

# Data Source
In this project i have collected images dataset from kaggle.com

# Technologies Used  
FrontEnd: HTML/CSS/Javascript
BackEnd: Flask
Object Recognition: Deep Learning (vgg16)

# Snapshots
![image](https://user-images.githubusercontent.com/72505248/174105257-dc4c1f19-70c5-48a6-a652-c2376d99853a.png)
![image](https://user-images.githubusercontent.com/72505248/174105306-7222af99-7541-4bdd-9a20-a146155cdd3d.png)
