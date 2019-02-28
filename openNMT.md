# Reference from [OpenNMT Official Site](http://opennmt.net/OpenNMT-py/main.html#installation)

# Manual for openNMT installation
  This manual will guide you through openNMT installation using PyTorch.

*We assume that you have python3 already installed and 'pip3' the python3 package installer and your OS is assumed to be Linux(ideally Ubuntu)*

## Step1 * [Install PyTorch](https://pytorch.org/) *

    pip3 install torch torchvision

**If you are having python2 version then you may use the below command.**

    pip install torch torchvision

 While this package downloads and installs you may have a cup of tea as this will take a while. Remember you need to have good internet connection as this package is about 582.5MB.

## Step2 *Clone the OpenNMT-py repository*

    git clone https://github.com/OpenNMT/OpenNMT-py
    cd OpenNMT-py

## Step3 *Install required libraries*

   pip3 install -r requirements.txt

### For python2 use 

   pip install -r requirements.txt

### Thats it now you are ready to take off. To get familiarize about how to use openNMT follow the [link](http://opennmt.net/OpenNMT-py/quickstart.html)
