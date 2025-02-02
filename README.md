# PoseCNN-implementation

Follow the pose_estimation jupyter notebook for step by step implementation of the Paper PoseCNN for 6D pose estimaiton. You can train your own model with this notebook!

## Dataset 

We will use the props dataset provided by the University of Michigan's PROGRESS lab led by Professor Chad Jenkins. Here is a snapshot of the dataset and what it should look like once it's passed through the dataloader. 
<p align="center">
    <img src="utils/Screenshot from 2025-02-02 17-32-02.png" alt="alt text">
</p>

## Implementing the Segmentatino Branch

The segmentation branch fuses feature from the feature extracted from the backbone. After training the inference from the jupiter notebook should look like this.
<p align="center">
    <img src="utils/Screenshot from 2025-02-02 17-32-24.png" alt="alt text" width="45%">
    <img src="utils/Screenshot from 2025-02-02 17-48-38.png" alt="alt text" width="45%" style="margin-left: 10px;">
</p>


## Implemening the Rotation and Translation branches along with the hough voting layer

The implementations are given in the corresponding python file and the necessary inference code is also provided. Once the branches are ready to go you can train and load up your model in the notebook. the final result after the inference shold look like this with many other photocs in the notebook as well. this is just one of the few from the test split of the dataset.

<p align="center">
    <img src="utils/Screenshot from 2025-02-02 17-49-57.png" alt="alt text">
</p>

