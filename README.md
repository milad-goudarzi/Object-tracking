# Tracking and counting vehicles
This project is about counting vehicles in a video. In first glance, it looks like detecting vehicles and counting them would lead us to what we want. However, this is true only for images and not videos. In videos, the whole process, i.e., object detection, will be repeated on each frame and therefore if our video has say 30 frames per second, each vehicle will be counted 30 times in each second of the video and it is obviously wrong. So, in addition to object detection, we need to have a technique to determine if we have already counted a vehicle and this could be achieved by tracking vehicles.

## Demo

<h3 align="center"> Bridge viewpoint</h3>

https://github.com/milad-goudarzi/Object-tracking/assets/20543988/e8a6063c-80e3-49e9-aa62-235f8f042255


<h3 align="center"> Cluttered environment with numerous vehicles far from camera</h3>

https://github.com/milad-goudarzi/Object-tracking/assets/20543988/a6bbc3e0-886f-4126-a68c-e2f077fbfc03

<hr>
<b> This project is done by mainly using these three packages: </b>
<ul>
  <li><a href="https://github.com/ifzhang/ByteTrack"> ByteTrack </a></li>
  <li><a href="https://github.com/ultralytics/ultralytics"> Ultralytics </a></li>
  <li><a href="https://pypi.org/project/opencv-python/4.7.0.72/"> OpenCV </a></li>
</ul>

## How to use
To run this project, you can follow the instructions written in the `Counting vehicles.ipynb` notebook.
## Contact me
Fastest way to contact me is by shooting me an email at: milad.goudarzi@mail.polimi.it
