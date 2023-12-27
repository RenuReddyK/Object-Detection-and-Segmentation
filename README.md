# Object-Detection-and-Segmentation

## YOLO:
Implemented from scratch based on the original research paper, YOLO (You Only Look Once) is a real-time object detection algorithm that efficiently processes images in a single pass, providing high accuracy and speed.
<p align="center">

Original Image | Image with Predicted Label NMS
--- | ---
 ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/7a634f35-b57b-46e3-953d-0aa4dd916b56") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/7db9d191-d82d-4216-ae4b-b3127014cdb3) 
 </p>

## SOLO:
Developed from the ground up using research paper insights, SOLO (Segmentation of Objects by Learning Only) is a sophisticated instance segmentation model that excels in precisely delineating individual object instances within an image.
<p align="center">
  
Original Image | Image with Predicted Mask
--- | ---
 ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/fa800270-5553-4b41-9d57-a93becefd7b0") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/150eda5b-2ea7-419c-8215-e4d1f4f8de97) 
 </p>

## SegFormer:
Constructed from the research paper, SegFormer is a cutting-edge semantic segmentation model that adopts a transformer-based architecture, demonstrating state-of-the-art performance in pixel-level image segmentation tasks.
<p align="center">
  
Ground Truth | Original Image | Predicted Mask 
--- | --- | ---
 ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/83cafdda-c438-4fbb-a709-68bb7b6cfb62") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/723824a5-d104-45c3-b7a8-0d240d989128) | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/708d8ba6-4b13-487d-9c96-24f4c657906f)
</p>

## VAE:
Implemented a Variational Autoencoder (VAE) on the Fashion MNIST dataset involving training a neural network architecture to learn a probabilistic mapping of input images to a latent space. 
<p align="center">

Original Image | Reconstructed Image 
--- | ---
 ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/5f676a68-d718-4a6c-a5bd-72b0d58296d3") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/0b5bd2f9-af69-4f5a-9b51-dde66833ee32)
 </p>

## CycleGAN:
Constructed from scratch following the research paper, CycleGAN on STL-10 dataset. It is a powerful unsupervised learning model that facilitates domain adaptation by mapping images from one domain to another without paired training data, showcasing impressive results in image-to-image translation tasks.
<p align="center">
 
GAN Generated Images at epoch 15 | GAN Generated Images at epoch 30 | GAN Generated Images at epoch 45 
--- | --- | ---
 ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/6f007a68-e2d3-474d-9b39-48c8c9ded937") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/3178bf31-c701-41b9-a06a-c98b7659853d) | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/598220f9-78d8-4d05-9e84-c16388da55f0) 

GAN Generated Images at epoch 60 | GAN Generated Images at epoch 75 | GAN Generated Images at epoch 90
--- | --- | ---
![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/599806fc-d728-4770-9baf-60867fce4840") | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/69f84535-d990-4b1b-89f6-2be56867d959) | ![](https://github.com/RenuReddyK/Object-Detection-and-Segmentation/assets/68454938/b2eed21c-a27f-41f0-a10b-22dc7a3c1c1c)

</p>


# References:
[1] https://doi.org/10.48550/arXiv.1506.02640 <br>
[2] https://doi.org/10.48550/arXiv.1912.04488 <br>
[3] https://doi.org/10.48550/arXiv.2105.15203 <br>
[4] Diederik P Kingma and Max Welling. Auto-encoding variational bayes. arXiv preprint arXiv:1312.6114, 2013. <br>
[5] IanGoodfellow,JeanPouget-Abadie,MehdiMirza,BingXu,DavidWarde-Farley,SherjilOzair,Aaron Courville, and Yoshua Bengio. Generative adversarial nets. In Advances in neural information pro- cessing systems, pages 2672–2680, 2014. <br>
[6] Jun-Yan Zhu, Taesung Park, Phillip Isola, and Alexei A Efros. Unpaired image-to-image translation using cycle-consistent adversarial networks. In Proceedings of the IEEE international conference on computer vision, pages 2223–2232, 2017.
