# TrafficSense
Deep Learning model to determine the amount signal time required at an intersection depending on the number of vehicles, accounting for two wheelers, three wheelers, LMVs, LCVs, HCVs, etc. 
The dataset used here is trafficCAM (https://arxiv.org/abs/2211.09620). The model determines the amount of time required at an intersection depending on the amount of traffic there is in the lane. A traffic flow formula is used that accounts for the amount of two wheelers, LMVs and HMVs, and the weather. 
The model is constructed using the pretrained ResNET50 model and some custom layers. 
