# User perspective dataset for 6-DoF point cloud video
The user perspective dataset was recorded while 40 participants watched 150 looped frames of point cloud video content in the Unity game engine and the 4 point cloud videos from the 8i voxelized full bodies dataset. The location and orientation of their viewport is recorded at every rendered frame. All coordinates are based on the Unity world coordinate system. The XZ plane at the origin represents the floor, and the dataset contains the following fields:

* (1) FrameNumber: The frame number for the current point cloud frame being rendered
* (2) HMDPX: The X coordinate of the viewport
* (3) HMDPY: The Y coordinate of the viewport
* (4) HMDPZ: The Z coordinate of the viewport
* (5) HMDRX: The rotation of the viewport about the X axis
* (6) HMDRY: The rotation of the viewport about the Y axis
* (7) HMDRZ: The rotation of the viewport about the Z axis
* (8) Participant: Identifier for the current participant
* (9) Dataset: Identifier for the current point cloud sequence
* (10) Viewframe: Frame number in the current session across multiple playback loops

# Reference
We kindly ask that should you mention our dataset in your publication, that you would reference the following paper:
* [1]. J. Li, X. Wang, Z. Liu, and Q. Li, “A QoE Model in Point Cloud Video Streaming,” 2021, arXiv:2111.02985.
* [2]. Zhi, Liu, Qiyue Li, Xianfu Chen, Celimuge Wu, Susumu Ishihara, Jie Li, and Yusheng Ji. "Point Cloud Video Streaming: Challenges and Solutions." IEEE Network (2021). 

