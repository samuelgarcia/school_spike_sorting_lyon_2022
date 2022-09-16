# SpikeInterface Tutorial -  SI new API (versio>=0.95)  - Sep 2022

This tutorial has been presented in Lyon for the GDR neuralnet 2022 workshop.

In this tutorial, we will cover the basics of using SpikeInterface for extracellular analysis and spike sorting comparison. 
We will be using the new `spikeinterface` version from the SpikeInterface github organization. 

For this analysis, we will use a 64-channel dataset from am "ASSY-156-P1" probe from Cambridge Neurotech. 
The dataset is provided by Samuel McKenzie. 

### Table of contents

We recommend creating a new `si_env` conda environment using:

`conda env create -f environment.yml`

from this page https://github.com/SpikeInterface/spikeinterface/tree/master/installation_tips



Alternatively, you can install the requirements you can use the `requirements.txt` in this directory by running the command:

`pip install -r requirements.txt`

In addition, it is recommended to install [docker-desktop](https://www.docker.com/products/docker-desktop/), as this will enable us to run 
multiple spike sorters without installation!


### Downloading the recording

First, we need to download the recording. Feel free to use your own recordings as well later on. 
From this [drive link](https://drive.google.com/drive/folders/1DuPMypbwLGfBQmXT2NOlDiUS_QVnCQFd?usp=sharing), you can download the dataset mentioned above (`cambridge_data.dat`) (~1.5 GB). 
The recording was performed with the "ASSY-156-P1" probe with 4 shanks of 16 channels (in total 64 channels).
