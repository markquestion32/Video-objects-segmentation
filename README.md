# Video-objects-segmentation
A comparaison between the two image segmentation models

Segmenting regions of interest in videos is critical for numerous computer vision applications,
such as scene understanding, action recognition, and video editing. Two advanced methods for video
segmentation are YOLOv8 and CLIPSeg. YOLOv8 is an efficient object detection and segmentation
model known for its speed and accuracy, integrating real-time instance segmentation. In contrast,
CLIPSeg employs contrastive language-image pretraining, allowing zero-shot segmentation driven by
textual prompts without the need for task-specific training.

# YOLO (You Only Look Once)
The YOLO algorithm is a state-of-the-art object detection and segmentation framework widely
used in computer vision tasks. Unlike traditional detection methods similar to those used in TP1 that
apply classifiers or detectors at multiple locations within an image, YOLO processes the entire image
at once, predicting the bounding boxes, class probabilities, and segmentation masks in one forward
pass. This approach enhances both detection speed and accuracy.
![image](https://github.com/user-attachments/assets/038fa8d4-90c6-4853-a9d2-16023a3a6ce2)
# CLIPSeg Zero-Shot
CLIPSeg is a zero-shot segmentation framework that combines the vision-language capabili-
ties of the CLIP model (seen in the last TP) with pixel-level segmentation tasks. Unlike traditional
segmentation models, CLIPSeg can perform segmentation without any training data specific to the
segmentation task, which can make it adaptable to new scenarios but can sometimes hinder its perfor-
mance.

![image](https://github.com/user-attachments/assets/4ebfccb6-30a4-4c7b-92fe-125c8f462348)

Overall, these experiments highlight differing strengths between YOLOv8 and CLIP-seg. While
YOLOv8 excelled at segmenting small or distant objects and offered faster inference, CLIP-seg demon-
strated impressive semantic fidelity, performing notably well in detecting moving objects. These find-
ings suggest that choosing between the two models should be guided by specific task requirements:
YOLOv8 is more suitable for scenarios demanding real-time performance and accurate detection of
tiny or faraway targets, whereas CLIP-seg may be advantageous in situations where semantic consis-
tency and nuanced object interpretation are paramount. Future work could explore hybrid approaches
that combine the speed and localization prowess of YOLOv8 with the rich semantic understanding of
CLIP-based methods.
Page 12 of 12

