# WA_LabelAutomation
Label Automation project for Wisconsin Automomous   
**google Dochttps**://docs.google.com/document/d/1g9b7wFROa8i7EBsxHF1rCQbYmJT1sswlYSrG-jdHVAw/edit  
**bdd100k**: https://www.vis.xyz/bdd100k/  

## **Tools**  
Use CVAT to greate labels for the image and export it using the YOLO format. https://www.cvat.ai/

## **TODO**  
Find some batter Models that do the label auto  

## **Tasks**  
For now, we should first create labels for 
  - **traffic signs** (stop sign, yield, speed limit, rail road crossing, ext)  
  - **pedestrians**  
  - **cars**

Gieve **Cars** and **People** higher priority
  
Then move onto traffic cones, barrels, and barricades. Last and most difficult will be deer.  
For traffic lights, our object detection doesn't care about state of traffic light, we have post classification for that, so no we just want to know where the traffic light as and do not care about the state for right now.  

To start, we should divide up the tasks. First, we’ll identify an object detection module or model. Once we’ve selected the best one, we’ll focus on outputting labels on a large scale. Before that, we’ll upload initial labels and files to the GitHub repository for organization and tracking. Once everything is functioning well, we’ll request large-scale cloud storage and generate 10k images per class, as cloud storage can be costly.  

each people focus on some class of image and find the model for that image.   



## **YOLO v8**  
https://huggingface.co/Ultralytics/YOLOv8








