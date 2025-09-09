# white-headed-Langur
This project builds a deep learning based call detection model to detect the calls of adult male white headed langurs in audio files recorded by automatic recording units, and ultimately find the audio containing the target call among many recordings.

![Model](image/Model.png)

# Initialization

## Setup

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yhzdsk/XXX.git
cd xxx
```

## Dependencies

Our implementation is based on [PyTorch](https://pytorch.org). We recommend using `conda` to create the environment and install dependencies.Select the appropriate `cudatoolkit` version according to your system:

```
conda create --name XXX python=3.8
conda activate XXX
conda install pytorch==2.0.1 torchvision==0.15.2 pytorch-cuda=11.8 -c pytorch -c nvidia
pip install -r requirements.txt
```
