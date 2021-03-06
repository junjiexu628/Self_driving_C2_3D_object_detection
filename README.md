# Self_driving_C2_3D_object_detection
## Section 1 : Compute Lidar Point-Cloud from Range Image

> Find and display 6 examples of vehicles with varying degrees of visibility in the point-cloud
> Identify vehicle features that appear as a stable feature on most vehicles (e.g. rear-bumper, tail-lights) and describe them briefly. Also, use the range image viewer from the last example to underpin your findings using the lidar intensity channel.
### Range images
![task1_range_image1](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task1.PNG)
![task1_range_image2](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task1_range_img1.PNG)

### Images with Intensity
![task1_intensity](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task1_intensity1.PNG)

### Point cloud Images
![task2_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_PCL_vehicles.PNG)
![task2_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_pcl1.PNG)
![task2_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_pcl2.PNG)
![task2_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_pcl3.PNG)

#### Details on the Point Cloud Images
![details_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_zoom1.PNG)

- On the left of ego car, five full vehicles are detected and half vehicle is showed. On the close distance, the hood, roof, windshield, even outer side mirror and car body of the vehicle are clear to show. on the far distance, only the hood and car body are show clearly.

![details_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_zoom2.PNG)

- on the right of ego car, there is very big vehicle, it seems truck with big rear body. It seems the bottom part of the trunk is clear, but the upper part of the truck cannot be detected. Or the upper part of the truck has nothing.


![details_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_zoom4.PNG)

- On the front of the truck, there are 4 vehicles. Just the rear part of the vehicle are showed. 

## Section 2 : Create Birds-Eye View from Lidar PCL

![BEV_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task3_bev1.PNG)

![BEV_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task4_intensity1.PNG)

## Section 3 : Model-based Object Detection in BEV Image
- Based on the fpn-resnet config model

- Point cloud image on frame 1
![BEV_detection](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/frame1_pcl1.PNG)

- Camrea image on frame 1
![BEV_detection](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/frame1_detect1.PNG)

- Detection image with bounding box on frame 1
![BEV_detection](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/frame1_detect2.PNG)

- Detection image with bounding box on frame 2
![BEV_detection](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/frame3_detect1.PNG)
![BEV_detection](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/frame3_detect2.PNG)

## Section 4 : Performance Evaluation for Object Detection

- Based on the default darknet config model
- The object detection performance shows the FN is higher than the FP when the min.IOU is 0.5. More vehicle cannot be detected, less is detected wrong.
![eval_detection](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/det3_mAP1.PNG)
![eval_detection](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/det3_mAP2.PNG)

# Acknowledgement
All mentors in Udacity and all students on the knowledge platform. Your answers and support gives me great help. Appreciate all of you.


