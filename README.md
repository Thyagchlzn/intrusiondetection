<br/>
<p align="center">
  <a href="https://github.com/Thyagchlzn/intrusiondetection">
    <img src="https://cdn-icons-png.flaticon.com/512/189/189484.png?w=740&t=st=1682321869~exp=1682322469~hmac= 5d4a228d5e55099c675ca8d149aeb782665fcdb43f5ec3a1688f924c779099bb" alt="Logo" width="80" height="80">
  </a>

  <h2 align="center">Intrusion detection in real time based on YOLOV7 </h2>

  
</p>



## About The Project

![Screen Shot](https://raw.githubusercontent.com/Thyagchlzn/intrusiondetection/main/snapshots/live_video_using_webcam.png?raw=True)

The project is a valuable addition to enhance surveillance systems. It  involves real-time video analysis and object detection to identify intrusions within a specified bounding box. 
1. **Input Sources:** The system supports both live video feeds through USB and pre-recorded videos. This allows users to use different sources for monitoring and analysis.

2. **Bounding Box Input:** Users are required to draw bounding boxes around areas of interest where they want to detect intrusions. These bounding boxes can be of any shape, allowing flexibility in defining the regions for surveillance.

3. **Object Detection:** The system performs object detection within the specified bounding box to identify any objects that are not part of the initial setup. It compares the detected objects with a user-defined list of allowed and unallowed objects.

4. **Intrusion Detection:** An intrusion is detected when an unallowed object appears inside the bounding box. If any unauthorized object is detected, the system flags it as an intrusion.

5. **Email Notifications:** When an intrusion is detected, the system sends an email notification to the user. The email contains an image of the intrusion taking place, providing visual evidence of the event.

6. **Customizable Intrusion Rules:** Users have the flexibility to define what kinds of objects should be considered intrusions. This customization allows them to adapt the system to specific surveillance needs.

7. **Intrusion-Free Zones:** Users can designate certain areas within the frame as intrusion-free zones by drawing bounding boxes over those regions. This feature prevents false alarms caused by authorized objects in predefined safe areas.


### Prerequisites



```sh
pip install -r requirements.txt

pip install -r requirements_flask.txt
```
If your device supports cuda 
```sh
pip install -r requirements_gpu.txt
```

### Installation


 Clone the repo

```sh
git clone https://github.com/Thyagchlzn/intrusiondetection.git
```

### Working

1. Sign in using a mail-id
<br/>

![Screen Shot](https://raw.githubusercontent.com/Thyagchlzn/intrusiondetection/main/snapshots/signup_page.png?raw=True)


2. Log in using the main-id
<br/>

![Screen Shot](https://raw.githubusercontent.com/Thyagchlzn/intrusiondetection/main/snapshots/login_page.png?raw=True)


3. Enter the type of object along with source details
<br/>

![Screen Shot](https://raw.githubusercontent.com/Thyagchlzn/intrusiondetection/main/snapshots/getting_input_from_user.png?raw=True)


4. If an intrusion occurs ,intruder image will be sent to your e-mail
<br/>

![Screen Shot](https://raw.githubusercontent.com/Thyagchlzn/intrusiondetection/main/snapshots/mail_notification.jpg?raw=True)


**References:**

* [IEEE Paper](https://r.search.yahoo.com/_ylt=AwrO.pEmhcJkevsM3t1XNyoA;_ylu=Y29sbwNncTEEcG9zAzEEdnRpZANBREVOR1QyXzEEc2VjA3Ny/RV=2/RE=1690498470/RO=10/RU=https%3a%2f%2fieeexplore.ieee.org%2fabstract%2fdocument%2f9117960/RK=2/RS=G5.cNqApo0vEUOKwuXhkV0YZ1xw-)
* [Yolov7 implementation](https://github.com/WongKinYiu/yolov7)
  


