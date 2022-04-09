# KITTI-Multi-Object-Detection-Tracking-Detectron2
Multi-Object Detection and Tracking using Detectron2's pre-trained Mask-RCNN on the KITTI MOTS dataset.

**Process:**
- Detectron2 is a library by Facebook. It contains many pretrained models and other useful features for CV tasks.
- The pretrained model I have used is the "Cityscapes/mask_rcnn_R_50_FPN", which was trained on the Cityscapes dataset for instance segmentation.
- The model has been trained on both the KITTI MOTS data set and the MOTSChallenge dataset. 

**Current results:**
- Model evaluation is yet to be done.
- Current results visualized: 
![Alt Text](https://github.com/kevinbtw-codes/KITTI-Multi-Object-Detection-Tracking-Detectron2/blob/main/results.gif?raw=true)
  
**To-do:**
- [x] Visualize results as videos
- [x] Add more pedestrian data
- [ ] Evaluate the model
- [ ] Tracked objects lose their class labels. To be fixed
- [ ] Make each tracked object have a different color
- [ ] Update the code to make it easily understandable by anyone
