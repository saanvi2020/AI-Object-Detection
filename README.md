# 🤖 AI-Object-Detection 

**👋 Overview:**
This project utilizes web technologies to create a real-time object detection application using a device's camera. The user interface includes options to toggle the object detection feature and adjust the frames per second (fps). The application draws on the capabilities of machine learning models to identify and annotate objects within the camera feed.

**📌 Key Features:**

⁘ User Interface:
Toggle Switch: Enables or disables the object detection feature.
FPS Slider: Adjusts the frames per second for real-time processing.

⁘ Camera Integration:
Utilizes the getUserMedia API to access the user's camera feed. Dynamically adjusts the canvas resolution based on the device screen size and camera feed dimensions.

⁘ Real-time Object Detection:
Integrates an object detection model (presumably loaded externally as objectDetector) to analyze frames from the camera feed. Bounding boxes, labels, and confidence scores are drawn on the canvas in real-time to highlight detected objects.

**📜Implementation Details:**

⁘ Camera Access:
Uses the navigator.mediaDevices.getUserMedia method to access the camera. Handles camera permission issues and retries if necessary.

⁘ Real-time Processing:
Implements a timer callback (timerCallback) to continuously process frames from the camera feed. Adjusts the canvas resolution to match the device screen and maintain aspect ratio.

⁘ Object Detection:
Calls the ai function to perform object detection on the current camera frame. Draws bounding boxes, labels, and confidence scores on the canvas for each detected object.

**🖥️ Technologies Used:**                                                                                                                                                                                    
  HTML                                                                                                                            
  CSS                                                                                                                                                                          
  Javascript                                                                                                                                                                                                         
  [Materialize](https://materializecss.com/)                                                                                                                                                                      
  [ml5js](https://ml5js.org/)

**🛜 Compatible Browsers:**                                                                                                                                                                                        
  Chrome                                                                                                                                                                                                
  Firefox                                                                                                                                                                                                     
  Microsoft Edge                                                                                                                                                                                             
  Brave                                                                                                                                                                                                             

**📷 Images:**
![Screenshot 2023-12-26 144846](https://github.com/saanvi2020/AI-Object-Detection/assets/129750954/aa1199e1-ea6e-49e3-b8a5-b078fd8b2ac2)
![Screenshot 2023-12-26 145135](https://github.com/saanvi2020/AI-Object-Detection/assets/129750954/73744526-34fe-4661-a67e-f6f32e60c473)






