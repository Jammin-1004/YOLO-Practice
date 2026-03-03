# YOLO-Pracitce-Object-Detection-
Using YOLOv11, Detection Practice.

Dataset Use, roboflow's rock-paper-scissors Computer Vision Model, 
2024-03-14 2:32pm, YOLOv11 Use.
Link: https://universe.roboflow.com/roboflow-58fyf/rock-paper-scissors-sxsw/dataset/14

"YOLOv11m" was used to detect people visible on CCTV footage.
![Uploading confusion_matrix_normalized.png…]()

To use YOLO, photo labeling (Bounding Box) and a .txt file with the same name as each photo are required.

Labeling was done using labelIMG, and the labeled photos were not attached to the project.

Afterwards, the training and practice described above were repeated to learn pedestrians and objects from CCTV footage required for the project.

The training results were very satisfactory. While there were many instances of object recognition failure or misrecognition when there were no landmarks or when objects were slightly similar, recognition was still successful.
