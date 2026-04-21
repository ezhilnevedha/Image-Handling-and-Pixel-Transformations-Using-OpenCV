# Image-Handling-and-Pixel-Transformations-Using-OpenCV
## Overview

This experiment demonstrates basic image handling and pixel-level transformations using OpenCV in Python. It focuses on loading images, displaying them, and performing drawing operations and simple transformations.

## Objectives
To understand how to read and display images using OpenCV.                                      
To learn color space conversion (BGR to RGB).                                               
To perform drawing operations such as lines, circles, rectangles, and text.                         
To explore basic pixel manipulation techniques.                                      

## Tools and Technologies
Python                                     
OpenCV (cv2)                               
Matplotlib                            
## Requirements                          

Make sure the following libraries are installed:

`pip install opencv-python matplotlib`
## Experiment Steps
### 1. Image Loading
Images are loaded using cv2.imread().                       
The default format is BGR.
### 2. Color Conversion
Convert BGR to RGB using:                                  
`cv2.cvtColor(image, cv2.COLOR_BGR2RGB)`                                          
Required for correct display using Matplotlib.                                    
### 3. Displaying Image
Images are displayed using Matplotlib:                                      
`plt.imshow(image)                                        
plt.title("Image")                                                 
plt.axis('off')                                             
plt.show() `                                            
### 4. Drawing Operations
Line Drawing                                            
Draw a line using:                                                   
`cv2.line(image, start_point, end_point, color, thickness) `                                        
Circle Drawing                                             
Draw a circle using:                                           
`cv2.circle(image, center, radius, color, thickness)  `                              
Rectangle Drawing                                
Draw a rectangle using:                                      
`cv2.rectangle(image, top_left, bottom_right, color, thickness)  `                                 
Adding Text                                                   
Add text using:                                                
`cv2.putText(image, text, position, font, font_scale, color, thickness)`                             
### 5. Pixel Transformations      
Basic pixel-level operations include:                              
Accessing pixel values                                      
Modifying pixel intensities                                                 
Understanding image dimensions using image.shape                              
Sample Workflow                                              
Load image using OpenCV.                                             
Convert image to RGB.                                                   
Display original image.                                         
Apply drawing functions (line, circle, rectangle, text).                              
Display modified images.                                                  
## Output                
Original image                    
Image with line                         
Image with circle                          
Image with rectangle                               
Image with text                            
## Learning Outcomes                             
Understanding of image representation in OpenCV.                         
Ability to perform basic image manipulations.                               
Familiarity with coordinate systems in images.                                   
Knowledge of pixel-level operations.                                
## Conclusion

This experiment provides a foundation for image processing using OpenCV. It introduces essential concepts such as image loading, color conversion, and drawing operations, which are useful for advanced computer vision tasks.
