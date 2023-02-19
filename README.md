# (HoMi) Real Time Heart Rate Monitoring System

## Overview
Heart rate monitoring is a common practice that is used to measure the number of times the heart beats per minute. This measure, known as the heart rate, is an important indicator of overall health and can help doctors diagnose and treat a variety of medical conditions.

Heart rate monitors can be used in a variety of settings, including hospitals, fitness centers, and even at home. In hospitals, heart rate monitors are often used to monitor the heart's activity in real-time, allowing doctors to quickly respond to any changes in heart rate. In fitness centers, heart rate monitors are used to help people track their heart rate during exercise, allowing them to adjust their workout intensity to achieve their fitness goals.

Overall, heart rate monitoring is a valuable tool for both doctors and individuals. It can help diagnose medical conditions, monitor the effectiveness of treatments, and even improve physical fitness. As technology continues to advance, it is likely that heart rate monitoring will become an even more important part of healthcare and fitness in the future.

## Inspiration
Our motivation behind making this remote real-time heart rate monitoring system is to provide a convenient and effective way to monitor a person’s heart without the need to be in a hospital or clinic. Remote operation is especially useful in fitness and exercises alongside medical applications for patients with heart conditions.

In the fitness and exercise setting, a remote heart rate monitor can help a person track their heart rate during physical activity. This can be helpful for several reasons. For example, monitoring heart rate can help a person ensure that they are exercising at the right intensity level to reach their fitness goals. It can also help them avoid overexertion and prevent injury.

In a medical setting, the heart rate monitor can be used to monitor a patient's heart rate remotely. This can be especially useful for patients who have heart conditions that require frequent monitoring. The information can be shared with family and friends along with the medical authorities in case of an emergency.

Overall, our heart rate monitor can help people stay healthy and achieve their goals in a convenient and effective way as it can be integrated into a regular camera.

## What it does
HoMi is a real-time remote heart-rate monitoring system that offers a convenient and effective way to remotely monitor a person's heart rate without the need for a smartwatch, hospital, or clinic.

## How we built it
### Methodology
To measure heart rate remotely we have used a method called Eulorean Video Magnification (EVM) to reveal temporal variations in the video that are difficult or impossible to see with the naked eye. Using this magnification we take a standard video sequence as input and apply spatial decomposition followed by temporal filtering. The resulting signal is then amplified to reveal hidden information. Using this method we are able to visualize the flow of blood as it fills the face and also amplifies to reveal small motions in real time.

The technique employs a combination of spatial and temporal processing to highlight subtle changes in a video sequence.

###Codebase
We have used Python for this project with OpenCV and NumPy libraries.

We have used OpenCV for face detection and NumPy for all mathematical formulations.

## Challenges we ran into
Implementing the EVM algo.
Object detection with OpenCV.
Manipulation of NumPy arrays and getting results out of them.
Adding a test case when the forehead is covered.
Detecting face movement and calculating heart rate accordingly.

## Accomplishments that we're proud of
Implementation of EVM algorithm.
Object Detection with OpenCV.
No heart rate is detected when the forehead is covered.
No heart rate is detected when no one is in the boundary frame.
Heart rate in normal and exercise condition.
Finally, achieving an accuracy of 94% when compared with Apple smartwatch reading.
What we learned
Implementation of object detection with OpenCV
Implementation of EVM algorithm and NumPy arrays
Image processing
Video processing
Reading separate RGB frames
## What's next for HoMi
Adding remote real-time measurement for respiration rate or oxygen levels.
This application can be integrated with treadmills and other gym equipment.
All of these functionalities can be integrated into the Flask web application so that any user can remotely measure their heart rate, respiration rate, or oxygen levels.
We can link the application with machine learning for sentiment analysis, which means that heart rate can be used to predict a person's level of stress, mood, or anger.
