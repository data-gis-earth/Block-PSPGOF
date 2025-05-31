# Introduction
This repository contains the dataset of the paper "Block-PSPGOF:High quality Mesh Reconstruction of Large Scenes Based on Progressively Self-Planarized Gaussian Opacity Field".  
Both the Power Station and Rural datasets were generated using industry drones. During the aerial photography process, these drones not only capture aerial images but also provide real-time, accurate camera poses. After image acquisition, the images along with their respective poses are imported into professional 3D modeling software, where they undergo manual trimming to produce a detailed model of the scene. This refined model ensures that the volume error is less than 5 cm and serves as the ground truth mesh.

# Dataset
You can download the Dataset by this link [BaiDu Yun](https://pan.baidu.com/s/1TtI2ktSqrqIVHE0cfeZbLw) and the password is **_mmyr_**.  

# Dataset structure
    ├─ Rural                           # Dataset name  
        ├─ images                      # Images captured by drone  
        ├─ gt
            └─ point_cloud.ply         # Ground truth point cloud
        ├─ val.json                    # image names for validation  
        └─ geo_registration.txt        # The camera position corresponding to the image  
    └─ PowerStation                    # Dataset name  
        ├─ images                      # Images captured by drone  
        ├─ gt
            └─ point_cloud.ply         # Ground truth point cloud
        ├─ val.json                    # image names for validation  
        └─ geo_registration.txt        # The camera position corresponding to the image 
