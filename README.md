


# Multi-Object-Tracking
In this project, I compare two SOTA Multi-Object Tracking (MOT) algorithms: (a) Yolov5+DeepSORT and (b) FairMOT. 

# Implementation
Both the models are trained on multiple MOT datasets and then evaluated on MOT16 dataset. MOT16 dataset was not used for training these models. One of the sample tracked output of each model is shown below. We can clearly see better MOTA, lesser False Positives and lesser Identity Switches in FairMOT video compared to the Yolov5+DeepSORT video. 

Following two repositories were used for the model implementations:
- Yolov5 + DeepSORT: https://github.com/mikel-brostrom/Yolov5_DeepSort_Pytorch
- FairMOT: https://github.com/ifzhang/FairMOT

# Weights and Biases Report
For short explanations on the workings of both the models, followed by more qualitative and quantitative comparisons, please visit this report: https://wandb.ai/vbagal/Multi-Object%20Tracking/reports/Yolov5_DeepSort-vs-FairMOT--Vmlldzo4Nzk0MjQ


Link to the papers:
- FairMOT: https://arxiv.org/abs/2004.01888
- DeepSORT: https://arxiv.org/abs/1703.07402

# Yolov5 + DeepSORT Tracking
https://user-images.githubusercontent.com/51148252/127759388-6eb32007-8a35-465c-bd2b-e3fa4cb5fead.mp4

# FairMOT Tracking
https://user-images.githubusercontent.com/51148252/127759399-2cd14a71-b8e1-4b97-9897-b9a0c74f5c0e.mp4

