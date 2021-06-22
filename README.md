# GANInvert
 Study on two papers.

This is the repository for my course The Application of AR and VR Technology.

I chose Closed-Form Factorization of Latent Semantics in GANs(https://arxiv.org/pdf/2007.06600.pdf) and tried to understand the paper. The paper comes up with an approach which is capable
of not only finding semantically meaningful dimensions. Then I found out that GAN inversion is needed to process real images with GAN, so I read In-Domain GAN Inversion for Real Image Editing(https://arxiv.org/pdf/2004.00049.pdf), which shows how to find the latent code, giving the original image.

Code in the folder "genforce" in the repository is copied from the official implementation of the latter papaer, since I am not able to build StyleGAN or the GAN inverter myself.
