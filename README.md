# Introduction
Hello everyone. This is Mohammad. I was surfing git hub projects about Persian license plate detectors and i realized that a few programmers write license detectors and most of other people just forked their repository and published that as their own name and that was not complete too for example in a high quality image of the plate number 12 was detected 17 by the program. So i decided to train whole network myself with a higher detection accuracy.
# Model Description
First plates are extracted by yolo-8 and cropped. I trained the model with @iran-license-plate-yolo downloaded from kaggle which contains picture of cards and their plates. The annotation contains plates location in the image from top corner to the bottom. At the end of training this stage we achieved mAP50 of 0.871 and mAP50-95 of 0.581.
The image below shows how plated are extracted from images:
1.PNG

                   
