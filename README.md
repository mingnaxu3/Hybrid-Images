# Hybrid-Images
Using an image filtering function, create hybrid images that change in interpretation as a function of the viewing distance of the image. 

<img width="404" height="355" alt="Screenshot 2026-01-14 at 8 40 35 PM" src="https://github.com/user-attachments/assets/7645583c-da0b-4a2e-ac11-a5f3a4d963d1" />

Using the concepts that high frequency dominates perception when it is available, but lower frequency dominates perception at greater distances, we are able to create a hybrid image that leads to different interpretations at different distances. 

**Image Filtering**: implemented the convolution function from scratch to filter the image. 

**Gaussian Blur**: Blurred the image by implementing a Gaussian blur, which takes a weighted average of neighboring pixels, which produces a kernel of a specified height and width that can be used with the convolution function to produce a blurred version of the image. 

**High and Low Pass Filters**: Implemented the high pass filter, which keepts only the fine details, and the low pass filters, which only retains the low level structures. 

**Hybrid Images**: By combining the sum of the low pass filtered image with the high pass filtered image, and controlling the cutt-off frequency amount, which tells us how much high and low frequency to remove and leave in the image. 

