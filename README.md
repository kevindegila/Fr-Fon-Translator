# FR-Fon-Translator

By [Kevin Degila](https://www.kevindegila.com/)


[TakwimuLab](https://takwimulab.gitlab.io/)

## Usage

Clone this repo and this one : https://github.com/joeynmt/joeynmt

In the joeynmt repo execute:
```sh
pip install .
```

Create a Conda virtual environment if you have Anaconda or Miniconda installed
```sh
conda create -n translator python=3.6
```
Activate the environment:
```sh
conda activate translator
```
In this repo,
Install the required packages:
```sh
pip install -r requirements.txt
```
Download the model from this google drive folder and put it in the frfon_transformer folder:
https://drive.google.com/open?id=12HmU5E9hUB5sInoWdjujGtFxYztQolXk

And Execute this command to start making predictions
```sh
python3 -m joeynmt translate "config.yaml" 
```

### Credits

Thanks to the [Masakhane](https://github.com/masakhane-io/masakhane) project for providing everything needed to start this project: data, code and guidance.

Thanks to [JoeyNMT](https://github.com/joeynmt/joeynmt) used for training and inference
