# Tracking and counting vehicles
This project is about counting vehicles in a video. In first glance, it looks like detecting vehicles and counting them would lead us to what we want. However, this is true only for images and not videos. In videos, the whole process, i.e., object detection, will be repeated on each frame and therefore if our video has say 30 frames per second, each vehicle will be counted 30 times and it is obviously wrong. So, in addition to object detection, we need to have a technique to determine if we have already counted a vehicle and this could be achieved by tracking vehicles.




