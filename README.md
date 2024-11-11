# Development of Lightweight RBF-DRNN and Automated Framework for CNC Tool-Wear Prediction
This repository contains the dataset and code for implementing the RBF-DRNN (Radial Basis Function - Deep Recurrent Neural Network) model, as presented in the paper [Development of Lightweight RBF-DRNN and Automated Framework for CNC Tool-Wear Prediction](https://ieeexplore.ieee.org/document/9748893).

## Overview
The model is implemented using TensorFlow and designed for tool wear analysis. The dataset used in this study comes from the [2010 PHM Society Conference Data Challenge](https://phmsociety.org/phm_competition/2010-phm-society-conference-data-challenge/), a widely recognized benchmark for tool wear analysis. Various studies have used this dataset to evaluate and compare predictive models for wear detection and prognosis.

## Dataset Details
The dataset used in this study is the **PHM 2010 dataset**, which includes measurements collected during milling operations. The key experimental parameters are as follows:

* Spindle speed: 10,400 RPM
* Feed rate: 1,555 mm/min
* Y depth of cut (radial): 0.125 mm
* Z depth of cut (axial): 0.2 mm
* Sampling rate: 50 kHz per channel

This dataset contains multiple sensor readings (vibration) captured during tool operation, which are critical for wear analysis.

## Usage
To use the model, follow the instructions in the code file. Make sure to install the necessary dependencies used in the  file, and ensure that the dataset is properly formatted for input into the model.

## Citation
[Development of Lightweight RBF-DRNN and Automated Framework for CNC Tool-Wear Prediction](https://ieeexplore.ieee.org/document/9748893)
```
@ARTICLE{9748893,
  author={Chiu, Sheng-Min and Chen, Yi-Chung and Kuo, Cheng-Ju and Hung, Li-Chun and Hung, Min-Hsiung and Chen, Chao-Chun and Lee, Chiang},
  journal={IEEE Transactions on Instrumentation and Measurement}, 
  title={Development of Lightweight RBF-DRNN and Automated Framework for CNC Tool-Wear Prediction}, 
  year={2022},
  volume={71},
  pages={1-11},
  doi={10.1109/TIM.2022.3164063}}
```
