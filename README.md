# YOLO-Object-Detection-Dataset-Pipeline

This Jupyter notebook implements a production-ready data curation pipeline for deep learning object detection models like YOLO, Faster R-CNN, or DETR using the Mapillary Traffic Sign Dataset (MTSDv2).

KEY FEATURES

Automatically selects top-5 traffic sign classes (other-sign, yield, pedestrian-crossing, no-entry, chevron-left)

Samples 100 images per class with deduplication for balanced datasets

Generates COCO-format compatible splits ready for YOLO annotation converters

Handles multi-object detection challenges: scale variation, occlusion, lighting extremes

Outputs curated train/val/test folders + class frequency JSON for training monitoring

Perfect foundation for training robust traffic sign detectors deployable in autonomous driving or smart city applications.

