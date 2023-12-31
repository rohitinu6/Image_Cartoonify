# Image_Cartoonify

## Aim: 
The purpose of this project is to Cartoonify an image i.e. to display an image in a cartoon form

## Working:
The cartoon image conatains two basic elements in it:
1. The boundary of the image object
2. The color of the image

To do this we are using the following image:

![1 (1009)](https://github.com/rohitinu6/Image_Cartoonify/assets/113301503/5b6d29ac-5c4d-4b1d-a531-345f166fce1e)

In the next step we create an image containg the boundaries/ edges of the inage after converting it into a grayscale image:

![download](https://github.com/rohitinu6/Image_Cartoonify/assets/113301503/c7894694-fe81-4e09-b7e2-3171576a539b)

Then we make a smoothened image of the original color image:

![download](https://github.com/rohitinu6/Image_Cartoonify/assets/113301503/63c075d9-3014-4da3-adf4-7b74c7b5af41)


## Output:

In the final step, we merge the smoothened and the edged image so as toobtain the cartoonified image, which is the desired output:

![download](https://github.com/rohitinu6/Image_Cartoonify/assets/113301503/8cf37c0a-4031-4b63-94c6-c094896f8c5d)

## Dataset:
The image used in this project is collected from the following Kaggle dataset:

https://www.kaggle.com/datasets/ashwingupta3012/human-faces

## References:
I have taken help from the following websites to understand the concept and build the project:

1. https://data-flair.training/blogs/cartoonify-image-opencv-python/
2. https://www.analyticsvidhya.com/blog/2022/06/cartoonify-image-using-opencv-and-python/
3. https://www.codespeedy.com/cartooning-of-an-image-in-machine-learning-using-python/
4. https://medium.com/boundlessinfo/a-mini-project-with-opencv-in-python-cartoonify-an-image-d82b9ff6df70
