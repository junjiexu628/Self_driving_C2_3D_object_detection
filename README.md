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
On the left of ego car, five full vehicles are detected and half vehicle is showed. On the close distance, the hood, roof, windshield, even outer side mirror and car body of the vehicle are clear to show. on the far distance, only the hood and car body are show clearly.

![details_PCL](https://github.com/junjiexu628/Self_driving_C2_3D_object_detection/blob/main/images/task2_zoom2.PNG)
on the right of ego car, there is very big vehicle, it seems truck with big rear body. It seems the bottom part of the trunk is clear, but the upper part of the truck
