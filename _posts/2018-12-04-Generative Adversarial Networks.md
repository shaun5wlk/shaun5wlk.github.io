---
layout:    post
title:    "Generative Adversarial Networks"
subtitle:    'continuously updated with recent GAN ideas'
author:    "Zpl"
header-img:   "img/post-bg-GAN.jpg"
tags:
  - GAN
  - Deep Learning
---

>I will update this article continuously with recent published ideas.

### What I cannot create, I do not understand. — Richard Feynman
Generative Adversarial Networks is a generative model proposed by Goodfellow et.al. in 2014,which has been one of the most popular algorithms in Deep Learning since then.We can understand it as a supervised map from a low dimensional,simple latent distributions to arbitrarily complex data distributions.Duo to its experimental effectiveness,it has been widely used 
to generate images and other types of data,like text.

More importantly,this model brings an adversarial learning idea which has been used in various tasks and proved to be excellent empirically,for example,[Adversarial Auto-encoder](),[adversarial feature learning](https://arxiv.org/abs/1605.09782).

Another change is that it drew our attention to the study of distance or divergence of distributions.In the initial paper [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661),they adopt Jensen-Shannon divergence to measure the distance of real and fake samples.But it is invalid most of the time,except the two distributions have disjoint support.[Wasserstein GAN]() has been proposed recently in consideration of the problem we encountered with JS-divergence and proved to be state-of-the-art improvement.

Note:sometimes we are more apt to call **distance** of distribution as **divergence** as it doesn't meet the condition of triangle inequality.
>Next I will give a simple introduction to initial Generative Adversarial Networks.You can check the paper of [Goodfellow et.al](https://arxiv.org/abs/1406.2661). to have a more clear comprehension.

#### Chapter 1.Generative Adversarial Networks.



**Reference**

[Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)
> In chapter 2,I will give a introduction to study about Wasserstein GAN,including the initial idea and other subsequent studies.
#### Chapter 2.Wasserstein GAN.
