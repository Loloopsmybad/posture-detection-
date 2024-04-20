

https://github.com/Loloopsmybad/posture-detection-/assets/93466068/18cd7925-3fe9-4c58-9745-0c83ff1052b9

# requirments !! install these before use !!
opencv-python <= 3.7.9
mediapipe
opencv


# posture-detection-
checks for bad posture 

uses mediapipe model for pose estimation and detection 

# working 

prameters for checking the posture 
the programs picks up the landmarks detected from the model and draws tangent from them 

if slope is not in the desired range --> wrong posture 

if posture is in the desired range --> correct posture 



