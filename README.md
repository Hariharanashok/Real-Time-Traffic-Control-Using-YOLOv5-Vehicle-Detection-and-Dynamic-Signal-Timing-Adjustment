## Real-Time Traffic Control Using YOLOv5:Vehicle Detection and Dynamic Signal Timing Adjustment
This project, titled "Real-Time Traffic Control Using YOLOv5: Vehicle Detection and Dynamic Signal Timing Adjustment," involves developing an intelligent traffic management system aimed at optimizing urban traffic flow. By leveraging YOLOv5, a state-of-the-art object detection model, this system identifies vehicle density in real-time from video feeds, dynamically adjusting signal timings to prioritize lanes with higher traffic. This responsive traffic signal control improves overall efficiency by reducing congestion and enhancing commuter experience.

## About
Real-Time Traffic Control Using YOLOv5: Vehicle Detection and Dynamic Signal Timing Adjustment is a project focused on creating an adaptive traffic management system that utilizes YOLOv5, a cutting-edge object detection model, to monitor vehicle density in real-time. Traditional traffic signal systems rely on fixed timings, which can result in inefficient traffic flow, especially during peak hours. This project addresses these limitations by detecting vehicles in designated zones and dynamically adjusting signal timings based on current traffic conditions. Through this responsive approach, the system aims to reduce congestion and improve the overall driving experience by prioritizing heavily trafficked lanes and adapting to fluctuating traffic patterns in urban environments.

## Features
<!--List the features of the project as shown below-->
- Utilizes advanced YOLOv5 deep learning model for real-time vehicle detection.
- Dynamic signal timing adjustment based on live traffic density data.
- Scalable framework suitable for deployment in multi-lane urban intersections.
- Low latency and high processing speed for immediate traffic flow adjustments.
- Implementing polygon zone , to detect and get the count of vehicles.
- Configurable polygon zones to focus on specific high-density traffic areas.
## Requirements
<!--List the requirements of the project as shown below-->
* YOLOv5 - The notebook uses a YOLOv5 model for vehicle detection. The model is cloned from GitHub, and its requirements are installed via a requirements.txt file within the YOLOv5 repository.
* Python Libraries :
* torch - Essential for YOLOv5 model operations, specifically for handling deep learning computations and CUDA support.
* supervision - Used for object detection, drawing annotations, and handling polygon zones to detect vehicles within specific areas.
* numpy - Utilized for array manipulations, specifically for defining polygon zones and processing detections.
* opencv-python (cv2) - Assists in video processing and image handling, including reading and writing video files.
* IPython.display - For displaying images and video outputs within the notebook.
* nvidia-smi and nvcc - System utilities used to confirm GPU support for CUDA, necessary for accelerating deep learning operations with YOLOv5
## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![Screenshot 2023-11-25 134037](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/8c2b6b5c-5ed2-4ec4-b18e-5b6625402c16)

#### Output2 - Name of the output
![Screenshot 2023-11-25 134253](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/5e05c981-05ca-4aaa-aea2-d918dcf25cb7)

Detection Accuracy: 96.7%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
The Sign Language Detection System enhances accessibility for individuals with hearing and speech impairments, providing a valuable tool for inclusive communication. The project's integration of computer vision and deep learning showcases its potential for intuitive and interactive human-computer interaction.

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
1. N. S. Gupta, S. K. Rout, S. Barik, R. R. Kalangi, and B. Swampa, “Enhancing Heart Disease Prediction Accuracy Through Hybrid Machine Learning Methods ”, EAI Endorsed Trans IoT, vol. 10, Mar. 2024.
2. A. A. BIN ZAINUDDIN, “Enhancing IoT Security: A Synergy of Machine Learning, Artificial Intelligence, and Blockchain”, Data Science Insights, vol. 2, no. 1, Feb. 2024.




