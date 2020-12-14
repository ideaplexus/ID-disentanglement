# COMING SOON !

<p align="center">
<img src="docs/teaser.png" width="800px"/>
</p>

## Description   
Official Implementation of our paper for both training and evaluation.

> **Face Identity Disentanglement via Latent Space Mapping**<br>
> Yotam Nitzan<sup>1</sup>, Amit Bermano<sup>1</sup>, Yangyan Li<sup>2</sup>, Daniel Cohen-Or<sup>1</sup><br>
> <sup>1</sup>Tel-Aviv University, <sup>2</sup>Alibaba <br>
> https://arxiv.org/abs/2005.07728
>
> <p align="justify"><b>Abstract:</b> <i>Learning disentangled representations of data is a fundamental problem in artificial intelligence. Specifically, disentangled latent representations allow generative models to control and compose the disentangled factors in the synthesis process. Current methods, however, require extensive supervision and training, or instead, noticeably compromise quality. In this paper, we present a method that learns how to represent data in a disentangled way, with minimal supervision, manifested solely using available pre-trained networks. Our key insight is to decouple the processes of disentanglement and synthesis, by employing a leading pre-trained unconditional image generator, such as StyleGAN. By learning to map into its latent space, we leverage both its state-of-the-art quality, and its rich and expressive latent space, without the burden of training it. We demonstrate our approach on the complex and high dimensional domain of human heads. We evaluate our method qualitatively and quantitatively, and exhibit its success with de-identification operations and with temporal identity coherency in image sequences. Through extensive experimentation, we show that our method successfully disentangles identity from other facial attributes, surpassing existing methods, even though they require more training and supervision.</i></p>

## Citation
If you use this code for your research, please cite our paper using:

```
@article{Nitzan2020FaceID,
  title={Face identity disentanglement via latent space mapping},
  author={Yotam Nitzan and A. Bermano and Yangyan Li and D. Cohen-Or},
  journal={ACM Transactions on Graphics (TOG)},
  year={2020},
  volume={39},
  pages={1 - 14}
}
```