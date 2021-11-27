[transfer-learning-attack.ipynb](https://github.com/WileyCorning/CS782-poison-frogs/blob/master/transfer-learning-attack.ipynb) contains the attack; other files are largely scraps and can be ignored.

This project uses Python3 with the latest version of Tensorflow. CUDA with cuDNN is recommended to speed up the training process.

The pretrained model and associated datasets should be downloaded automatically by Keras. To execute the poision attack, I manually copied the `cats_and_dogs_filtered` folder to an adjacent `cats_and_dogs_filtered_p` folder, which is where the poison image is latter added. (This is an ugly kludge!) **You will need to reproduce this step yourself to run the notebook**, but it's pretty straightforward.
