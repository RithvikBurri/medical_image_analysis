# Medical Image Classification with YOLOv8

Interactive Python project applying the YOLOv8 object detection model to classify brain MRI scans into four categories: **Pituitary**, **Meningioma**, **Glioma**, and **No Tumor**. This project investigates the potential of general-purpose computer vision models in the medical imaging domain.

## Purpose

Demonstrates the adaptation of real-time object detection models for use in healthcare. The project evaluates YOLOv8's ability to accurately detect brain tumors from MRI scans, helping bridge the gap between machine learning research and clinical diagnostics.

## Results

Evaluated on a 100-image test set with the following performance metrics:

* **Precision:** 87.6%
* **Recall:** 92.0%
* **mAP@0.5:** Strong detection performance at standard IoU threshold
* **mAP@0.5:0.95:** Moderate accuracy across stricter IoU ranges

## Skills Learned

Throughout the development of this project, I gained hands-on experience and strengthened my skills in:

* **Computer Vision:** Applying YOLOv8 to domain-specific datasets
* **Medical Imaging:** Understanding tumor types and MRI perspectives
* **Deep Learning Workflows:** Dataset preparation, model training, and evaluation
* **Performance Analysis:** Interpreting mAP, precision, and recall in a healthcare context
* **Reproducible Research:** Structuring experiments and results for clear reporting
