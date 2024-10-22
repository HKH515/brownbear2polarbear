# brownbear2polarbear
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hkh515/brownbear2polarbear)

Experiment using CycleGAN for Image to Image translation on images of brown bears and polar bears.

Please note that the model does **NOT** create accurate output, this is most likely due to the fact that the background of the images in A and B are not similiar.

<img src="./test_results/images/brown_bear_anchorage_zoo_real_A.png" width="45%"></img> <img src="./test_results/images/brown_bear_anchorage_zoo_fake_B.png" width="45%"></img>
<img src="./test_results/images/gallery5-7_real_A.png" width="45%"></img> <img src="./test_results/images/gallery5-7_fake_B.png" width="45%"></img>

## Setup for training
1. Create a folder in your google drive named `Colab Notebooks` (if it does not already exist)
2. Create a folder inside Colab Notebooks called `brownbear2polarbear`
3. Create a .zip archive called "trainA" containing a folder called "trainA" containing images of brown bears you would like to train the model on.
3. Create a .zip archive called "trainB" containing a folder called "trainB" containing images of polar bears you would like to train the model on.
4. Place this .zip archive inside the folder `brownbear2polarbear` that we created in step 2.
5. Copy the folder `brownbear2polarbear_checkpoint` to your google drive (inside `Colab Notebooks`, not `brownbear2polarbear`).
6. Now you should be ready to open `brownbear2polarbear_cyclegan.ipynb` in CoLab and run it, click the badge on the top of this page to open this in colab.
7. After running, the results should be stored in `brownbear2polarbear_results`, along with a copy in a folder labeled after the date and time of completing the run.

## Setup for testing
1. Create a folder in your google drive named `Colab Notebooks` (if it does not already exist)
2. Create a folder inside Colab Notebooks called `brownbear2polarbear`
3. Create a .zip archive called "testA" containing a folder called "testA" containing images of brown bears you would like to transform.
3. Create a .zip archive called "testB" containing a folder called "testB" containing images of polar bears you would like to transform.
4. Place this .zip archive inside the folder `brownbear2polarbear` that we created in step 2.
5. Copy the folder `brownbear2polarbear_checkpoint` to your google drive (inside `Colab Notebooks`, not `brownbear2polarbear`).
6. Now you should be ready to open `brownbear2polarbear_cyclegan_only_run_tests.ipynb` in CoLab and run it, click the badge on the top of this page to open this in colab.
7. After running, the results should be stored in `brownbear2polarbear_results`, along with a copy in a folder labeled after the date and time of completing the run.


## Copyright
All images are taken with permission for non-commercial and educational use from ImageNet.
