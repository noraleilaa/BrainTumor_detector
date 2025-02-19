
<img width="788" alt="Detector_output" src="https://github.com/user-attachments/assets/0e54b076-552f-45ca-b683-18add41a9bca" />

##YOLO v 8 Brain Tumor Detector 
Medical Image Dataset: Brain Tumor Detection
The Brain Tumor MRI dataset, curated by Roboflow Universe, is a comprehensive dataset designed for the detection and classification of brain tumors using advanced computer vision techniques. It comprises 3,903 MRI images categorized into four distinct classes:

Glioma: A tumor originating from glial cells in the brain.
Meningioma: Tumors arising from the meninges, the protective layers surrounding the brain and spinal cord.
Pituitary Tumor: Tumors located in the pituitary gland, affecting hormonal balance.
No Tumor: MRI scans that do not exhibit any tumor presence.
Each image in the dataset is annotated with bounding boxes to indicate tumor locations, facilitating object detection tasks precisely. The dataset is structured into training (70%), validation (20%), and test (10%) sets, ensuring a robust framework for model development and evaluation.

This implementation leverages Ultralytics YOLOv8, a state-of-the-art object detection architecture, to identify and localize brain tumors in MRI scans from the Roboflow Brain Tumor MRI dataset. 
The model is trained on 3,903 annotated MRI images across four critical classes: Glioma, Meningioma, Pituitary Tumor, and No Tumor, with bounding boxes precisely marking tumor regions. 
The dataset’s structured split (70% training, 20% validation, 10% testing) ensures robust evaluation of the model’s generalizability. The pipeline incorporates PyTorch for deep learning workflows, OpenCV for image preprocessing (resizing to 640x640 resolution),
and matplotlib for visualizing predictions. During inference, the model processes test images with a confidence threshold of 0.5, generating bounding box annotations overlayed on MRI scans to highlight tumor locations. Training employs advanced augmentation techniques (e.g., rotation, scaling, HSV adjustments)
to address medical imaging challenges like intensity variations and anatomical complexity. Performance is validated through metrics such as precision-recall curves, F1 scores, and confusion matrices, ensuring clinical relevance for assisting radiologists in early diagnosis and treatment planning. The system is 
designed for seamless integration into medical imaging workflows, prioritizing both accuracy and computational efficiency.

