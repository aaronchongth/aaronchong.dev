{
  "title": "VEGAN - Visual Enhancement GAN",
  "image": "/img/circleci-workflow.png",
  "link": "https://github.com/son-of-a-gan/vegan-paper/blob/master/ve-gan.pdf",
  "image": "/img/vegan-project-img-padded.png",
  "description": "Visual Enhancement GAN is a generative adversarial network trained to deblur images to be used as data for high speed applications, specifically in the self driving domain. We built on the work of Kupyn et. al to improve multiscale performance, introduced training with <em>Scaled Perceptual Loss, Smoothness Loss</em>, as well as using a <em>Random Scaled Crop</em> augmentation technique. Additionally we also introduced a <em>Fourier Domain Error</em>, as an way to better evaluate the performance of an image deblurring system.",
  "tags": ["Deblur", "GANs", "Computer Vision", "Synthetic Data", "Fourier", "PyTorch"],
  "fact": "",
  "featured":true
}

![](/img/vegan-project-img.png)

Visual Enhancement GAN is a generative adversarial network trained to deblur images to be used as data for high speed applications, specifically in the self driving domain. We built on the work of [Kupyn et. al](https://github.com/KupynOrest/DeblurGAN) to improve multiscale performance, introduced training with <em>Scaled Perceptual Loss, Smoothness Loss</em>, as well as using a <em>Random Scaled Crop</em> augmentation technique. Additionally we also introduced a <em>Fourier Domain Error</em>, as a way to better evaluate the performance of an image deblurring network. 

We also explored other evaluation methods such as <em>Image Segmentation Intersection Over Union</em> and <em>Perceptual Error</em>, with the goal to improve the capabilities of existing computer vision neural networks, as well as be able to quantify image sharpness and quality just like a human being.

Our final results showed that the model introduced with only the <em>Smoothness Loss</em> performed the best, while the <em>Fourier Domain Error</em> provided a much better way of evaluating the quality of the system. 

Check out our work [here](https://github.com/son-of-a-gan/vegan-paper/blob/master/ve-gan.pdf).
