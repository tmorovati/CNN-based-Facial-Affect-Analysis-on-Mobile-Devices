# CNN-based-Facial-Affect-Analysis-on-Mobile-Devices

In this repo, we tried to implement the paper, "CNN-based Facial Affect Analysis on Mobile Devices". The paper is add to the repo and you can download it. 

## Dataset 

Dataset is provided in this link:

https://drive.google.com/file/d/1MknXcvOW7FhQrtLWYJkti6MwvZBkwWgu/view

## Preprocessing

Since data is not balanced so we used the data augmentation to balance the classes. In the the dataset we have 8 different classes: 
["anger", "contempt", "disgust", "fear", "happy", "neutral", "sad", "suprise"]
We rotated(20 degrees), did the translation with respect to X and Y axis to % 10 percent and flipped images with repect to X axis.

## AlexNet Implementation

Architucture of the AlexNet is as below: 

![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/ba2a2fac-d23b-4c7b-b1c1-d93194b72e57)

We trained our model to 50 iterations, and the loss and accuracy plot are as below : 

![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/2123c2c8-ede9-4fa2-a75d-50fbe8d74b96)

## VGGNet

VGGNet Architecture is as below: 

![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/2070e5d6-db73-4f02-8c22-81b7578019ac)


We trained our model to 10 iterations, and the loss and accuracy plot are as below : 

![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/70ddd210-9322-4fc9-9248-f03994d3cf70)

![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/7f28d753-10cf-408c-a590-4c6c8744bfdc)


![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/3b4a302a-e255-4e48-9a43-2f5531a21d39)


## MobileNet

VGGNet Architecture is as below: 

![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/32398fcc-022a-40b3-a340-8525f7802e84)
We trained our model to 25 iterations, and the loss and accuracy plot are as below : 

![image](https://github.com/tmorovati/CNN-based-Facial-Affect-Analysis-on-Mobile-Devices/assets/47552594/dca0f752-6236-4df7-b132-6aa029a7e647)


if you have any questions, reach out to me via email: t.morovati.99@gmail.com

@article{DBLP:journals/corr/abs-1807-08775,
  author       = {Charlie Hewitt and
                  Hatice Gunes},
  title        = {CNN-based Facial Affect Analysis on Mobile Devices},
  journal      = {CoRR},
  volume       = {abs/1807.08775},
  year         = {2018},
  url          = {http://arxiv.org/abs/1807.08775},
  eprinttype    = {arXiv},
  eprint       = {1807.08775},
  timestamp    = {Mon, 13 Aug 2018 16:47:27 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-1807-08775.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
