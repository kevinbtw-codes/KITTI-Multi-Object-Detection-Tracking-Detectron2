# KITTI-Multi-Object-Detection-Tracking-Detectron2
Multi-Object Detection and Tracking using Detectron2's pre-trained Mask-RCNN on the KITTI MOTS dataset.

**Process:**
- Detectron2 is a library by Facebook. It contains many pretrained models and other useful features for CV tasks.
- The pretrained model I have used is the "Cityscapes/mask_rcnn_R_50_FPN", which was trained on the Cityscapes dataset for instance segmentation.
- The model has so far only been trained on the KITTI MOTS dataset. It can be improved with the MOTSChallenge dataset.

**Current results:**
- The model performs very well on cars, and not so well on pedestrians.
- Model evaluation is yet to be done.
- Results visualized:
  - (GIF to be added here)
  
**To-do:**
- [ ] Visualize results as videos
- [ ] Add more pedestrian data
- [ ] Tracked objects lose their class labels. To be fixed
- [ ] Tracked objects have different colored boxes in different frames. To be fixed
- [ ] Update the code to make it easily understandable
