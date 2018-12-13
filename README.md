# Intermediate Supervisors for Confidence Evaluation and Error-Guided Learning


The first goal of this project was to train a neural network (supervisor) to predict the error that another neural network (student) would make during the task of semantic segmentation. The student network is the DeepLab v2 network from https://github.com/speedinghzl/Pytorch-Deeplab. 

Pytorch >= 0.4.0 is required! The rest of the necessary modules can be found in the first cell of MKowal_Project.ipynb.

# RESULTS

The supervisor is trained on three types of error: binary class independant, binary class dependant, and multi-class. It achieves a maximum accuracy of over 40% meanIOU. The error guided learning is currently being worked on with no state-of-the-art results yet...

Done at Ryerson University, Toronto. Under the supervision of Kosta Derpanis (http://www.scs.ryerson.ca/kosta/) and Neil Bruce (http://www.scs.ryerson.ca/~bruce/)
