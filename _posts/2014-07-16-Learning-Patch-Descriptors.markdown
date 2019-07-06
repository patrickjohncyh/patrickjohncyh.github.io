---
layout: default
modal-id: 3
date: 2014-07-16
img: cabin.png
alt: image-alt
project-date: March 2019
<!-- client: Start Bootstrap -->
category: Deep Learning; Machine Vision; Patch Descriptor
description: The objective of this project is to use <strong>deep learning</strong> to learn <strong>robust vector descriptors</strong> for patches obtained from images. These patch descriptors can be used to more efficiently perform machine vision tasks such as Image Matching and Retrieval. In addition, noise was added to the patches to increase the difficulty of the task.</br></br> A <a href='https://arxiv.org/pdf/1505.04597.pdf'>U-Net</a> architecture was used in the first stage to perform image denoising. The denoised patches are put through a series of 2D Convolutions that is gradually bottlenecked to generate a 128x1 vector descriptor for an input patch.</br></br>Interestingly enough, a good architecture alone was not sufficient to attain good performance. In particular, I deployed In-Batch Hard Mining which uses a simple mathematical trick (dot-product) to generate many negative examples (different point in space) per positive example (same point in space) and use the hardest negative example. This was crucial for model performance as it makes very efficient use of the data and constantly forces the model to constantly imrpove as training progresses.</br></br>A crucial learning point in this project was exposure to not only reading academic papers but understanding and implementing them. A competition was held to determine the best model and my model came in <strong>1st Runner-Up</strong> amongst the entire cohort, and was able to attain <strong>state of the art</strong> performance.</br></br> My academic report can be found <a href='https://github.com/patrickjohncyh/patrickjohncyh.github.io/blob/master/docs/DL.pdf'>here</a>.
---
