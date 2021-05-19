# Smart_CCTV_for_fire_detection
##### ❗ Project in progress
#### This is the Computer-Vision Project of a PBL class for the first semester of 2021.(2021.03 ~ 2021.06)

- data : kaggle


<br/>

⭐Purpose of Project <br/>
First, It can detect fire situations quickly. <br/>
In addition, It detects people and animals in fire situations.

<br/>

⭐Process

#### 01. Image Classification
This classifies fire situations and non-fire situations.
If fire situation is detected, the system will proceed with the next process.

![image](https://user-images.githubusercontent.com/75927569/118815403-2e173e80-b8ec-11eb-80b8-162a5cc4f5cc.png)

<br/>

#### 02. Image Segmentation
Realistically, It is difficult to find some images of fire with people. 
We got about 200 pictures, but we think it's not enough.
Therefore, we try to synthesize people image mask in a fire image.
- Rembg
- [Reference](https://github.com/danielgatis/rembg.git)

![image](https://user-images.githubusercontent.com/75927569/118816283-fa88e400-b8ec-11eb-9a72-de97ef72ffe1.png)

⬇

![image](https://user-images.githubusercontent.com/75927569/118816391-17bdb280-b8ed-11eb-8e9f-0c081c94a55d.png)

<br/>

#### 03. Image Generation
![image](https://user-images.githubusercontent.com/75927569/118816477-2a37ec00-b8ed-11eb-92c2-5aeff260e3c7.png) <br/>
➕<br/>
![image](https://user-images.githubusercontent.com/75927569/118816503-30c66380-b8ed-11eb-9da5-c2729de24427.png)<br/>
⬇<br/>
![image](https://user-images.githubusercontent.com/75927569/118816527-358b1780-b8ed-11eb-951d-aa7663c6a7ac.png) <br/>


<br/>

#### 04. Image Detection
- mmdetection
![image](https://user-images.githubusercontent.com/75927569/118816587-49cf1480-b8ed-11eb-9b7d-3421561b0b11.png)



