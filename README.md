# feature_extractor

## Objectives

Given an image, the task is to identify the type of chart using various state-of-the-art image embedding and classification models and perform comparative analysis.

### Models considered

* VGG-19 

![image](https://user-images.githubusercontent.com/5688940/213294840-fef6604f-deef-4fe2-983d-4eaf154375b2.png)


* ResNet-152 
* Inception-v3 
* MobileNet
* Xception
    
[Data used for model training](https://d3c33hcgiwev3.cloudfront.net/l5TEkquFQuC8aYx7gYzXVA_92e632b18e37444695c031d7c31b04a1_coursera-chart-type.zip?Expires=1674172800&Signature=CtEw5UF647eTkSgmFp9xS2F9-apcwXmrD7Qw8UWm2GvG8yku~IUo4YznYhWdnemftrWchFhfyFTNrYbZ9whoTlG2yxq9ga74sgTpF4dDtkbLUcDGRrzXIac7iwX1aWwU72xZGKR9lTvluXkFFt4tsQCfsOrEMtSIQjzDGW8l5UQ_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

#### Implementation done under three scenarios provided below.

1. **Using Pretrained version:** Employ the respective pretrained versions (Pretrained on ImageNet dataset) as the    feature extractor. 

2. **Develop without using the pre-trained weights:** Train the model from head to toe on the provided dataset.

3. **Fine-tune the last two convolutional layers:**  This will train some parts of the network on the provided dataset, but some parts will be using its pre-trained weights.

## Output
<img width="671" alt="image" src="https://user-images.githubusercontent.com/5688940/213295310-191c63df-6845-463a-8afb-f748965bf95e.png">
