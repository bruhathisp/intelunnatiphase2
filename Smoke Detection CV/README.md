# Detecting Vehicle Smoke 
Vision-based vehicle smoke detection aims to locate the regions of vehicle smoke in video frames, which plays a vital role in intelligent surveillance. 
Existing methods mainly consider vehicle smoke detection as a problem of bounding-box-based detection or pixel-level semantic segmentation in the deep learning era, which struggle to address the trade-off of localization accuracy and speed. In addition, although various studies have been reported, there is no open benchmark available for real vehicle smoke detection. To address these issues, we propose a Polygon-based annotated Vehicle Smoke Segmentation dataset(PoVSSeg) and a block-wise vehicle smoke detection method.

# __PoVSSeg__ <br>
The PoVSSeg dataset encompasses a wide diversity in terms of road conditions (highway or urban), weather (sunny, cloudy, and rainy), vehicle types (bus, truck, and car), and smoke types which including 3,962 vehicle smoke images with polygon annotations. In addition, the PoVSSeg are randomly splited as traing set and test set, which contained 3812 and 150 images respectly. Figure. 1 illustrates some samples from the PoVSSeg. 





A dual-branch network with a main branch and an aggregation branch, for vehicle smoke detection. The main branch is designed for feature extraction, and the aggregation branch is for feature enhancement. With the help of the dual-branch architecture, can extract and aggregate features parallelly, which is more efficient than encoder-decoder structured models. 

![image](https://github.com/bruhathisp/intelunnatiphase2/assets/91585301/4ee9cb72-08ad-4960-8fc2-d3e6a4f4538b)
