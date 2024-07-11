# Object-Detection-and-Surface-Area-Calculation
## Introduction
This script detects objects in an image and calculates their surface areas, assuming the objects are 
rectangular.
## Approach
1. **Load the Image**: The script reads the image using OpenCV.
2. **Preprocess the Image**: Converts the image to grayscale and applies thresholding to create a 
binary image.
3. **Detect Objects**: Uses contour detection to identify objects in the binary image.
4. **Calculate Surface Area**: For each detected object, computes its bounding box and calculates 
the surface area assuming it is rectangular.
## Assumptions
- The objects in the image are assumed to be rectangular and lying flat on a surface.
- The surface area is calculated using the formula for a rectangle (width x height).
## Output
The script displays the image with detected objects highlighted and their surface areas annotated. It 
also prints the surface areas in the console.
Dependencies
1. OpenCV
2. NumPy
Key Algorithms Used 
1. Grayscale Conversion: Simplifies the image by reducing it to a single channel.
2. Thresholding: Segments the image into foreground and background.
3. Contour Detection: Identifies the boundaries of objects in the image.
4. Bounding Rectangle Calculation: Computes the smallest rectangle that can enclose each 
detected object.
5. Area Calculation: Calculates the surface area of the rectangular bounding boxes
