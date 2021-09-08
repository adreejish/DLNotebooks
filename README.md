# DLNotebooks
Collection of Jupyter Notebook implementations from Deep Learning Papers I find interesting

To run locally:
   ```sh
    pip3 install -r requirements.txt
    jupyter notebook
   ```
Create a folder within the directory named datasets and add relevant datasets.<br>
Please note that you're using Python3.7 or above 

### FSRCNN - Fast Super-Resolution Convolutional Neural Networks <br>
FSRCNN trained on DIV2K dataset and a scaling factor of 4 <br>
**paper** : [Accelerating the Super-Resolution Convolutional Neural Network,Chao Dong,et al.](https://arxiv.org/abs/1608.00367) <br>
**dataset** : [DIV2K dataset](https://www.kaggle.com/joe1995/div2k-dataset)<br>
**notebook** : [link](https://github.com/adreejish/DLNotebooks/blob/master/FSRCNN.ipynb)<br>
**model** : [link](https://github.com/adreejish/DLNotebooks/tree/master/models/fsrcnn)<br>

### DCGAN - Deep Convolutional Generative Adversarial Networks <br>
DCGAN trained on images of abstract art <br>
**paper** : [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks,Alec Radford, Luke Metz, Soumith Chintala](https://arxiv.org/abs/1511.06434) <br>
**dataset** : [Abstract art datset](https://www.kaggle.com/bryanb/abstract-art-gallery)<br>
**notebook** : [link](https://github.com/adreejish/DLNotebooks/blob/master/DCGAN.ipynb)<br>
**model** : [link](https://github.com/adreejish/DLNotebooks/tree/master/models/dcgan)<br>
code used for overriding train step from [here](https://www.tensorflow.org/tutorials/generative/dcgan)<br>
model checkpoints are not included in the repo for this implementation



