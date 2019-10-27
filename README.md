# human-motion-prediction

a general human motion prediction algorithm based on various order markov mixture model

current status
----------------------------
Predict future human motion base on learned human motion pattern and estimate the confidence of prediction online.

![visual servo control with obstacle avoidanc](https://github.com/william-in-kit/human-motion-prediction/blob/master/prediction.gif)

the algorithm can be easily extend to other application. the algorithm now consist of four parts: 
1. human pose estimation with help of openpose
2. various order markov mixture model for human motion pattern learning
3. human motion state estimation, motion intent strength and uncertainty
4. interaction multi model for self-adjusting prediction

the training input are RGB image now, but since the learning model is a general model, other motion data type like IMU or EMG signal can alse be used as input. 

