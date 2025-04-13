# Tensorflow Templates

## Install Ubuntu WSL

Update the Nvidia GPU drivers, and install CUDA Toolkit and cuDNN check [Install Tensorflow](https://www.tensorflow.org/install/pip) for versions.

Open the Control Panel and activate Windows features:

- Virtual Machine Platform
- Linux Subsystem

Restart the PC.

Open Windows Powershell and type:

wsl --install -d Ubuntu

Follow the instructions and start Ubuntu. Once open update the system typing

sudo apt update && sudo apt upgrade

Reestart Ubuntu.

## Install Tensorflow

Inside this repository create a virtual environment:

sudo apt install python3-venv

cd tf_templates

source venv\bin\activate

and install Tensorflow and other libraries:

pip install tensorflow[and-cuda]

pip install jupyter

pip install scikit-learn

pip install seaborn


## Malaria Dataset

Download the dataset from <https://drive.google.com/file/d/1Q0FN6wp1S299Uhcs96fAF5PuJRHyt0ef/view?usp=sharing>