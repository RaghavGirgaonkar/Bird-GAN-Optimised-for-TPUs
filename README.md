# Bird-GAN-Optimised-for-TPUs
A Deep Convolutional Generative Adversarial Network for creating Birds: optimised to run on Google's Tensor Processing Units.

The network was trained on the [Bird Dataset on Kaggle](https://www.kaggle.com/datasets/gpiosenka/100-bird-species) which has over 58000 images of birds across 400 different species. 

The architecture of the GAN was inspired by [this Face-GAN](https://github.com/jeffheaton/present/blob/master/youtube/gan/gans_scratch.ipynb).

The Google Colab notebook can be run [here](https://colab.research.google.com/drive/1_jerqSSkL0e0VvqUcAFx6uyFv6HgCCLO?usp=sharing), if you plan to use your own dataset you will need Google Cloud storage and will need to upload your dataset as a Tensorflow record file to run this notebook on TPUs.

Any comments or suggestions are welcome and feel free to contact us for the same! We'd also love to see any interesting birds that you may generate. 
Happy training!


# A few generated birds, 128x128 resolution
![Generated Birds](https://github.com/RaghavGirgaonkar/Bird-GAN-Optimised-for-TPUs/blob/main/images/bird_examples.jpeg?raw=true)

# Training montage for 600 epochs, 64X64 images
https://user-images.githubusercontent.com/33746851/178730263-42843f3f-2d19-4199-b103-d0d65193100b.mp4

