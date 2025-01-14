# A Implementation of Transferable Adversarial Attacks for Image and Video Object Detection

## 1. Introduction
- This code is the implementation of the paper [Transferable Adversarial Attacks for Image and Video Object Detection](https://arxiv.org/abs/1811.12641)
- This paper has been received by IJCAI-19.

## 2. Pretrain
https://drive.google.com/open?id=1PpffJyBNuF8jw6tetea3HVGij6CbrjbH

You can dowmload them as your pretrained model of fasterRCNN, thanks to the author Yun Chen for sharing.

## 3. Demo
After you modify the relevant configuration, just run this ipynb in colab.
 ```
 test.ipynb
 ```

## 4. Train
Just run this ipynb in colab.
 ```
 feature_and_attack_train.ipynb
 ```
## 5. Results
- Training this network cost a lot of time, evary iteration cost around 7s(running in colab), while once training is comleted, the speed of generating adversarial examples is quite fast.
- Due to the slow upload speed, we only show 7 examples in 'sdd' folder.

## Acknowledgement

This work was just slightly modified from this awesome github project:

- [Adversarial-Attacks-for-Image-and-Video-Object-Detection](<https://github.com/say2sarwar/Adversarial-Attacks-for-Image-and-Video-Object-Detection/tree/master/img_attack_with_attention>) .


