# BEV_GTool

### BEV Ground Truth Generation and Annotation Tool 
BEV GTool is a program that supports generating GT (ground truth) of automotive scenarios consisting of a video sequence and radar measurement. Besides the annotation boxes in the space, the tool considers the object state in BEV (bird's-eye view) space as well. Anyone can use it for non-commercial purposes. Since the application was designed in Matlab App Designer, it requires Matlab Runtime 9.11 installation.

![My image](https://github.com/lindenmaier94/BEV_GTool/blob/main/BEV_GTool_UI.png)

### Download Latest Executable
* [BEV GTool 1.0](https://github.com/lindenmaier94/BEV_GTool/releases/download/BEV_GTool_1_0/BEV_GTool_1_0.zip)
(only binary executables can be downloaded)

### Main Features
* Automatic Pre-Generation
  * automatically generating annotation boxes in image space by tracking the input detections
  * automatically generating the ground truth in BEV space by fusing the monocular tracks with radar detections
* Correcting the Pre-Generated Ground Truth
  * modifying the objects' position in BEV space
  * modifying the bounding box of the objects on the images
  * propagating the modifications by BEV tracking
  * creating new objects
  * deleting false detections/tracks
* Windows only

### Instructions
* Download and install [Matlab Runtime 9.11](https://ssd.mathworks.com/supportfiles/downloads/R2021b/Release/7/deployment_files/installer/complete/win64/MATLAB_Runtime_R2021b_Update_7_win64.zip)
* Unzip the downloaded release
* Run BEV_GTool_App.exe
* Load video
 * only MP4 format is accepted
* Load 
