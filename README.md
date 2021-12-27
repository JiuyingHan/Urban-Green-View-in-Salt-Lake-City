# Urban-Green-View-in-Salt-Lake-City
This project calculates the green view index of points along Salt Lake City street networks using PSPNet (https://github.com/hszhao/PSPNet) and Google Street View images. 

Points were first generated every 100m along street network, images heading 0, 60, 120, 180, 240, 300 degree were requested by Google Street View API for each point. Sementic segmentation with PSPNet was then used to segment pixels with green views. Mean percentage of green view pixels was calculated for each point as the green view index. Indexes were interpolated to create a raster layer.

# Result
![image](https://user-images.githubusercontent.com/90343611/147511449-b5b514d9-b91c-4fef-b608-4306e916b08c.png)

