# Tour-Into-Picture
## Motivation
*Team work for computer vision*

Trompe-l'œil (French for “deceive the eye”), originates with the artist Louis-Léopold Boilly. In ancient painting this meant creating the illusion of the third dimension on a two-dimensional surface with shading and perspective. We can just use a painting to depict the 3d world so why can’t we create an algorithm to reconstruct a 3D scene models from a lone image?   
Now we will introduce you to our ideas in this poster and let us go into the Picture!

## Team Members
- Mingcong Li  
- Runan Lyu  
- Qi Liao  
- Yubo Min  
- Li Xiao  

## How to use  
Please run the 'main.m', which is in the doc folder.    
### 1. Picture Selecting
Select a picture on the left side, the picture can be previewed in the middle. (Pictures 1-6 are system pictures, if you want to use other pictures, please select "your image”, and then select your picture).   

### 2.Foreground Cutting
Please select whether you want to skip the step of cutting out the foreground.  
(a) If you want to skip, please select "yes" (please wait for a few seconds until you can see “done!” in the comment).  

(b) If you do not want to skip, please select *"No"*, then a new window will pop up. Please click the consecutive points with the mouse in the new window to form a closed graph. The closed graph is your foreground. After clicking all the points, please press "Enter". 

![selecting the foreground](/Pic/choose_fore.png "choosing_foreground")
> Choosing the foreground

### 3.Rectangle Creating
Please click "start!" in "Step 2". Use the mouse to click two points in the pop-up window (the first point is the upper left corner of the rectangle, and the second point is the low right corner.). After clicking all the points, please press "Enter". In this step, if you think the points, that you have chosen, are not suitable, you can just choose these 2 points directly again.

### 4.Vanishing Point Selecting
Click "start!" in "Step 3". Click a point with the mouse in the popup window. After clicking the vanishing point, please press "Enter".  

### 5.Camera Position and Angle Adjusting
Click "go!" in "Step 4". In the pop-up window, you can use the keyboard to control the zoom in and out (zoom out [e] zoom in [q]), to control the camera position([h-k-u-j]) and to control the camera angle([w-s-a-d]).  

### 6.Picture Acquiring
After you adjust camera, enter [b] to get a screenshot. When the screenshot is taken successfully, you can see the pop-up message-window (msg - "Screenshot successfully!”). At this point you can find an image named "Screenshot" in the folder.  
If you are not satisfied with this image, please click "yes" in the pop-up message-window. Adjust the angular and position of camera again and enter [b] again to get a new screenshot.  
### 7.Quit
If you are satisfied with the screenshot, please enter [Esc] to end the control of keyboard. 

## Demonstration of Results
<p float="left">
  <img src="pic/result_before.jpg" width="50%" />
  <img src="pic/result_after.png" width="50%" /> 
</p>

## Common Errors
1.	*“You haven’t chosen an image! Please switch to another image and switch back to choose your image!”* (in step 1)  
You have chosen to use your own image, but you just close the window for choosing your own image.  

2.	*“You haven't chosen any points! Please do this step again or switch to the yes button!”* (in step 1)  
You have chosen to cut out the foreground, but you didn’t choose any points before pressing the enter.  

3.	*“You haven't chosen the points! Please do this step again!”*  (in step 2)  
You haven’t chosen any points and directly close the window or press enter.  

4.	*"You haven't chosen the points! Please do this step again!"* (in step 3)  
You haven’t chosen any points and directly close the window or press enter.  

5.	*"There is an error!"* (in step 4)  
Your directly close the window before press esc or you have done something wrong in the other steps.  




