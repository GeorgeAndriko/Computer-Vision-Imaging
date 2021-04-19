# Computer-Vision-Imaging

This project is concerned with Image Segmentation and Edge Detection.

1. Firstly, the code produces a binary image with the detected edges using only the blue channel of the original image.

  ![fruits](https://user-images.githubusercontent.com/74135164/115285939-2af72a00-a157-11eb-90ac-375e72fa3b32.jpg) 
Original Image

![output_1 1](https://user-images.githubusercontent.com/74135164/115285961-32b6ce80-a157-11eb-9355-f40165ece4b6.jpg) 
Binary Image

2. Secondly, there is a need to segment the objects in the image (fruits) based on the difference between the Green and Blue channels of the image (which at this case is greater than 30).

![output_1 2](https://user-images.githubusercontent.com/74135164/115286344-a48f1800-a157-11eb-82a2-a55d528094b9.jpg) 
Segmented Image.

3. At this stage, we need to decrease the cavities of the previous image in order to improve visibillity. Binary morphological operations were used.

![output_1 3](https://user-images.githubusercontent.com/74135164/115286968-60e8de00-a158-11eb-99fe-b42a5795a3ed.jpg)

4. Then, we managed to identify each and every fruit while displaying their boundary boxes.

![output_1 4-1](https://user-images.githubusercontent.com/74135164/115287430-eec4c900-a158-11eb-96a0-b9284ac8f798.jpg)
Identified Fruits.

5. Finally, our code identifies and prints segments of the image based on their RGB values. 

![output_1 4-2](https://user-images.githubusercontent.com/74135164/115288893-aad2c380-a15a-11eb-99a2-615be1a8de9f.jpg)

