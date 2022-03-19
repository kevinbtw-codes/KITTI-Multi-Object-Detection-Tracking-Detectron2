# KITTI-Multi-Object-Detection-Tracking-Detectron2
Multi-Object Detection and Tracking using Detectron2's pre-trained Mask-RCNN on the KITTI MOTS dataset.

## The model currently only works well on cars. More pedestrian data will be added in the next update.

**Process:**
- Detectron2 is a library by Facebook. It contains many pretrained models and other useful features for CV tasks.
- The pretrained model I have used is the "Cityscapes/mask_rcnn_R_50_FPN", which was trained on the Cityscapes dataset for instance segmentation.
- The model has so far only been trained on the KITTI MOTS dataset. It can be improved with the MOTSChallenge dataset, which has a lot more pedestrian data.

**Current results (*without extra pedestrian data*):**
- The model performs very well on cars, and not so well on pedestrians.
- Model evaluation is yet to be done.
- Current results visualized (**more pedestrian data needs to be added**): <br>
![Alt Text](https://github.com/kevinbtw-codes/KITTI-Multi-Object-Detection-Tracking-Detectron2/blob/main/result_without_pedestrian_data.gif)
  
**To-do:**
- [x] Visualize results as videos
- [ ] **Add more pedestrian data** [IN PROGRESS]
- [ ] Evaluate the model
- [ ] Tracked objects lose their class labels. To be fixed
- [ ] Make each tracked object have a different color
- [ ] Update the code to make it easily understandable by anyone
