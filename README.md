# Model-Compression-BQ

To create a virtual env and install Pytorch 1.9 cpu version
- python3 -m venv pytorch-venv
- source pytorch-venv/bin/activate
- pip3 install torch==1.9.0+cpu torchvision==0.10.0+cpu torchaudio==0.9.0 -f https://download.pytorch.org/whl/torch_stable.html



Run the gradient code train on a dummy CIFAR10 model 
-python3 model_gradients.py 



This is the implementation of B&Q algorithm from Speech Recogniton Model Compression (https://ieeexplore.ieee.org/document/9053927). 
In the original paper, we tested our algorithm on 4 models: 1. Speech command recognition, 2. DeepSpeech, 3. DeepSpeech2, 4. VGG16. 

In this repository, the automated code for B&Q will be shown for applying it as a standalone technique on multiple trained models. 
