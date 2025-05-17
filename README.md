# Fast-S_RCNN-_-Semantic_Segmentation
Fast SCNN Semantic Segmentation
This project implements Fast SCNN for semantic segmentation using TensorFlow on the CamVid dataset. It segments street scenes into 10 classes with up to 94.83% accuracy on some classes.
Setup

Clone the repo: git clone https://github.com/your-username/fast-scnn-camvid.git
Install dependencies: pip install -r requirements.txt
Download CamVid dataset: lih627/CamVid

Usage
Run training or inference with main.py:

Train: python main.py --mode train --data_path data/
Infer: python main.py --mode inference --model_path models/fast_scnn.h5

Reference

Fast-SCNN Paper

