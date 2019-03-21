---
title: "A novel focal Tversky loss function with improved Attention U-Net for lesion segmentation"
date: 2019-03-21T14:41:48-04:00
draft: false
---

+++
abstract = "\We propose a generalized focal loss function based on the Tversky index to address the issue of data imbalance in medical image segmentation. Compared to the commonly used Dice loss, our loss function achieves a better trade off between precision and recall when training on small structures such as lesions. To evaluate our loss function, we improve the attention U-Net model by incorporating an image pyramid to preserve contextual features. We experiment on the BUS 2017 dataset and ISIC 2018 dataset where lesions occupy 4.84% and 21.4% of the images area and improve segmentation accuracy when compared to the standard U-Net by 25.7% and 3.6%, respectively."

authors = ["Nabila Abraham*", "Naimul Mefraz Khan"]
date = "2018-12-18"

image = ""
image_preview = ""
math = true

publication_types = ["1"]
publication = "In International Symposium on Biomedical Imaging"
publication_short = "In *ISBI*" 

url_code = "https://github.com/nabsabraham/focal-tversky-unet"
url_dataset = ""
url_pdf = "pdf/my-paper-name.pdf"
url_project = ""
url_slides = ""
url_video = ""
+++
An improved loss function for medical image segmentation.