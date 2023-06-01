<h1 align="center">Personal Portfolio</h1>

```
All the projects shown in this portfolio are either personal projects or team projects which I contributed in.
The other contributers of each team project are mentioned in the portfolio footer.
```

A. [Robotics and Embedded Systems Projects](#a-robotics-and-embedded-systems-projects) <br />
B. [Machine and Deep Learning Projects](#b-machine-and-deep-learning-projects) <br />


<h2 align="center">A. Robotics and Embedded Systems Projects</h2>

<p align="center"> 
<a href="https://github.com/DohaElHady/RoboNurse" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/86476979/223711730-2ab0bdbf-0d69-41ef-b33c-27b58f045c20.png" alt="RONA" width="800" /> </a> </p>

### 1. Robot Nurse Assistant (RONA) [^1]

**Requirements/Aim:** Ease up the patients checkup process for some sections in the hospital as cardio, post anesthesia care unit, and infection control unit specially for the hospitals that can’t afford buying a care unit for each single room in it.<br />
**Technolgies:** Embedded Linux, Robotics, Cloud(Google Firebase), & Face Recognition. <br />
**Microcomputer:** Raspberry Pi 4B 8GB-RAM. <br />
**Programming Languages:** Python & Cpp. <br />
**Medical Integrated Sensors:**  Max30102 Spo2 Sensor, MLX90614 IR Temprature Sensor, & ECG Module.<br />
**Motion System:** Arduino Mega, 4 DC Motors, & Motor Controller. <br />
<br />
**Outcome:** [Demonstration Video]()<br />
**Research Paper:** [Robo-Nurse Healthcare Complete System Using Artificial Intelligence](https://link.springer.com/chapter/10.1007/978-3-031-03918-8_17) - Springer, The 8th International Conference on Advanced Machine Learning and Technologies and Applications·

**Personal contributions:** 
1. Set up RasbianOS on the Raspberry Pi.
2. Wrote Python code to control sensors using I2C communication protocol.
3. Wrote C++ code to control robot motion.
4. Built the robot GUI using Python Tkinter library.
<br />
<h2 align="center"> </h2>

<p align="center"> 
<a href="https://github.com/DohaElHady/GloveForDeaf" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/86476979/223726152-996acf33-c477-43d1-890e-3bfc3bdb8697.png" alt="glovefordeaf" width="800" /> </a> </p>


### 2. Glove for Deaf

**Requirements/Aim:** Design a glove that translates deaf sign language into text through LCD.<br />
**Technolgy:** Embedded Systems.<br />
**Microcontroller:** AVR(Atmega32A). <br />
**Programming Language:** Embedded C. <br />
**Hardware:** 5 Bend Sensors, 16*2 Blue LCD, & Amit Kit for interface.<br />
**Software Drivers:** DIO, ADC, LCD, Flex_sensor. <br />
**Outcome:** [Demonstration Video](https://github.com/DohaElHady/GloveForDeaf/blob/main/GloveForDeaf_Video.mov)<br />

<h2 align="center"> </h2>
<p align="center"> 
<a href="https://github.com/DohaElHady/TurtleBot3-ROS-Maze-Navigation" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/86476979/223705199-65a0bce0-92c0-4cc8-b6d2-bf77d8a3fd5c.png" alt="Turtlebot3 Navigation" width="800" /> </a> </p>

### 3. ROS-based Turtlebot3 Maze Navigation [^2]

**Requirements/Aim:** Autonomous navigation through lanes built of red tapes and walls, with the objective of reaching picking and placing locations from the robot’s home position by avoiding obstacles and manipulating objects, and finally returning back of the robot to its home.<br />
**Technolgies:** ROS & SLAM.<br />
**ROS Packages:** SLAM, Navigation, & Manipulation. <br />
**Outcome:** [Demonstration Video](https://github.com/DohaElHady/TurtleBot3-ROS-Maze-Navigation/blob/main/Demonstration%20Videos/Tasks%20Demonestration.mp4)<br />



<br /> 
<h2 align="center">B. Machine and Deep Learning Projects</h2>

<p align="center"> 
<a href="https://github.com/DohaElHady/Compiler-Provenance-Attribution" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/86476979/223572264-e004089b-2efa-4cec-b884-aa18c3db5ee6.png" alt="CompilerProvenance" width="800" /> </a> </p>


### 1. Compiler Provenance Attribution [^2]

**Problem:** Compiler type and optimization level classification for portable executables.<br />
**Technolgies:** Machine learning & deep learning.<br />
**Tools:** Jupyter Notebooks & Linux command-line.<br />
**Pythonic tool stack:** NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, & Tensorflow. <br />
**Results:** The best test accuracy of 100% was achieved by the stacking model for the classification of the compiler family, and 85.9%  for the optimization level by the deep learning model.<br />

**Personal contributions:** 
1. Automated the preprocessing of 100+ executable files through writing [Python disassembler script](https://github.com/DohaElHady/DatasetPreparation-LifeSaving-Scripts/blob/main/PortableExecutables-DatasetPreparation/PE_diassembler.py).
2. Cleaned the data in Python notebook through Pandas (droped nulls, splitted the data to train and test).
3. Applied feature engineering using ANOVA and Chi2 with k-fold cross validation.
4. Visualized the data using TSNE.
5. Built, trained, and tuned a deep neural network. 


<h2 align="center"> </h2>

<p align="center"> 
<a href="https://github.com/DohaElHady/Exterior-Car-Body-Parts-Localization" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/86476979/223578944-41748a39-f16c-4135-a19e-70190d3959d6.png" alt="BodyParts" width="800" /> </a> </p>

### 2. Car Exterior Body Parts Localization [^2]

**Problem:** Localize 14 exterior car body parts in case of no or partial damage.<br />
**Technolgies:** Deep learning using Yolov5 & Yolov8.<br />
**Tools:** Jupyter Notebooks.<br />
**Pythonic tool stack:** PyTorch. <br />
**Results:** The best test mAP of 91.8% was achieved by Yolov8.<br />

**Personal contributions:** 
1. Automated dataset annotations preparation through writing [Python annotations-convert script](https://github.com/DohaElHady/DatasetPreparation-LifeSaving-Scripts/blob/main/YOLO-CustomDatasetPreparation/YOLO_AnnotationsConvert.py).
2. Manually annotated images using Microsoft Visual Object Tagging Tool (VOTT).
3. Splitted the data to train and test.
4. Applied transfer learning and fine-tuning on YOLO model. 
5. Visualized the results using tensorboards.

<h2 align="center"> </h2>
<p align="center"> 
<a href="https://github.com/DohaElHady/ComputerVision-MicroProjects" target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/86476979/232062772-cd1d6ff1-80b9-4d39-8853-d4a69b202337.png" alt="Other Projects" width="800" /> </a> </p>

### 3. ComputerVision-MicroProjects
#### a. Birds Classification
1. Visualized data samples using Matliplot grids.
2. Built a fully victorized KNN model.
3. Trained SVM and Logistic Regression models.



[^1]: Contributors: 
[Doha ElHady](https://github.com/DohaElHady) - Mariam Essam - Asmaa Samir - Mariam Mohammed - [Omnia Mahmoud](https://github.com/omniahh) - Samaa Hany

[^2]: Contributors: 
[Doha ElHady](https://github.com/DohaElHady) - [Mohamed Elahl](https://github.com/MohamedElahl) - [Hassan Mohamed](https://github.com/Hsnmhmd) - [Karim Youssef](https://github.com/KarimYoussef98)

