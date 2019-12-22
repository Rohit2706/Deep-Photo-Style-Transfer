# Deep-Photo-Style-Transfer

The project intends to implement the original paper on Deep Photo Style Transfer by Luan. et. al. We have built a pytorch implementation of the original model built by the authors.

1. We have modified and built upon the publicly available pytorch implementation of Neural Style Transfer by Gatys. Et. al 

[Neural Style Transfer](https://pytorch.org/tutorials/advanced/neural_style_tutorial.html)

2. We have used the torch implementation of Matting Laplacian available on github. 

[Matting Laplacian](https://github.com/MarcoForte/closed-form-matting)

Our model makes the following assumptions:
1. Pretrained VGG19 as feature extractor for the images
2. Conv4_2 used for content loss and Conv1_1, Conv2_1, Conv3_1, Conv4_1, Conv5_1 used for style losses.
3. The input image is already photorealistic.
4. Weights as mentioned in the paper.

#### Results obtained are attached in the powerpoint presentation attached in this repository.

[Powerpoint Presentation](https://github.com/Rohit2706/Deep-Photo-Style-Transfer/blob/master/Deep%20Photo%20Style%20Transfer.pptx)

# References

### Original Paper:
Luan, Fujun, et al. "Deep photo style transfer." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017.

### Open Source Resources: 

https://pytorch.org/tutorials/advanced/neural_style_tutorial.html

https://github.com/MarcoForte/closed-form-matting

https://github.com/LouieYang/deep-photo-styletransfer-tf

# Credits

[Rohit Jain](https://github.com/Rohit2706)

Vaishnavi Kotturu

Khushi Gupta
