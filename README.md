# Image-Processing-Workshop

### Reading, Storing, and Video 
Because the image in Python is read as a matrix, we want to load images with OpenCV in the Datstracks,
Waitkey's command waits for the key event if we give the number as much as we said to wait here because we didn't give a number so much to wait until the keyboard is hit.
This order says that any window you opened, including the pinner you called and opened. The content of the image that is displayed is a matrix.
This code says: My rows are 600 and my image columns are 800, and because I have this coding, I use BGR or RGB codes if I go back to the dataset and see the right-click and property photo. Here it is 800 in 600 because it expresses Width*Hight in Windows
Depending on what suffix I give it, my matrix will turn this image with two extensive extensions for me to return Tro in the sense that I didn't have a problem.
What problem? The hard drive may not give me any problems that could not be assassinated, but Falls would return, if I go back to the folder, the two pictures are now, and we will find that PNG has more volume than JPG.
So it probably has no "PNG Press: Compression but JPG is so losing information on this press, image quality priority
And to show in Matt Plato Lib, this is a tool for drawing the chart. But we can use it to display images because the charts are HIT MAP based on the width and length of the heatsmarks, displaying a color in the output.
I now want to use it as a color image and imshone.
Actually, print the same image I see

I see a strange grocery and the colors have changed a lot. These colored perfects have been contracted to be RGB. But in OpenCV, it loads the channels to load the BGR
So I have to change the order of its channels:

I work with all the rows columns and channels from the beginning to the end we have the Array Slicing Numpy, but it is the reversal, that is, the first one is: 1:
As a result, I changed the order of the channels to see a quality image as before:: I can ... let me mean that all the Daimans, except for the next:

### OPENCV for this convert to us give orders:

In the end, it takes a switch and tells us what space our color is to change.
Just "do a simple color conversion, color_ types of colors we can do and here to convert BGR order here" to RGB, which is a singing syntax, and this is just a key and I could maintain its number. Here I write the letters written in the Great English so-called "Constant (they are fixed and make no meaning)

We cut it like this and I put it 4 but I was writing a bloody number because I might remember later and not know why.
If I remember this style we can find the information tab:
Finally, I can change the pixels of this numpy array because I knew in the name with Array Slicing I can manipulate the part of this array.
I loaded the photo here from the beginning and said that the rows 200 to 300 the columns of 500 to 300 and: all the color channels of 255, which means the highest color for all three channels.
I mean, in the end, I say white, why?

All three pixels have the highest amount of radiation, probably "it has the highest reflection and I see white, and if I used to print 0, none of these pixels would be clear.

And not turning on these pixels means that it is completely black,

And I can probably wear any color here.

In this color space if I mix the green and green.

By combining these two colors: I have yellow.

### Gray pictures:
How to have a gray level images:

I gray the image with the cvtcolor command: This makes the decisions gray
A simpler way of graying:

With data pass 0 to the Imread function I can read the photo gray
This function can say it has an optional parameter that if you don't pass the BGR, and if you pass, depending on what the number you see, it has something like changing the color channel and finally nakers this gray image and then I want to print the image slope.
When the image becomes gray, it differs from the color until it turns from the color, which means I have 600 rows and 800 columns:

And see three of the three numbers for the color image 0: Absolute Black and 255: Absolute White
And whatever between 0-255 is a level of gray
Now we can show these images with Matplotlib.

I expect a photo of black and white to give a gray photo but see the color?
Because we have different colors for drawing the graph and so-called the so-called colors to show the less color and the so-called.
Now if I tell her the Color map I want = Gray means I would like to be low 0: Black and more than 255 white.

And so we want to draw the same way
Take a look at the dimensions of the image and its comparison:

Home 10: Row and 50: Draw me for the column and three numbers are colored and colored. Is the so-called Topl
For Gray Scale, one of its methods is cvtcolor, and I re-printed the same poem that was more blue.
Because he has more Abby, I can say he has the most heaven and shows

 Here, because we have a number that 157 was the closer to the sky, the closer to the sky area, and how close the crab was to 0, to black, close to black,

That is, if I had a pixel on these gennels and trees, it would have been much closer to 0 than on the heaven, however, how did these three numbers reach 157?
If I understand this without using OpenCV, I can gray images myself. Just "with the matrix changes I know, they average, but the channels are different, and the channel is less important and the rejection is less important. The coefficients of these three are:

 They are almost 1.
So if I don't want to convert OPENCV, I can get the weighted average of these three channels for the entire image.


Channel No. 0+ Channel No.1 Channel 2 and each divided by 3 and each

And draw it:

Finally, I chose a smaller photo to see the output of the image just black and white:

### Mouse click event:



## What is the operation below the line to the line?

Be sure to have a mouse when you want to define a mouse event (usually working with the first 3)
Flag: I kept shift or not another button
Event: Mice Clicky -did- Middle Mouse-Mouse-Shakesmith- What happened
With a series of codes, we specified first:

X, y Paper says the moment of the mouse that should be returned to us
Very easily whenever you are going to move a circle
I told me to draw a circle on the image to a radius of 20 and its color I wrote the BGR combination and if I wrote negatively in the circle: It would draw a solid circle for me
In the next line, I draw a 512 x 512 and 3-channel matrix. From the image
In the next line, I just define it, I will continue to have a window called Image and work with that window.
Because this window is not known when setting up the cellar and working with that window.
In the next line, it says to define a mouse for a mouse, calling a function of a mouse
In what window to capture if something happened .. in a window called Image
I said to call the circular Drave function without the input parameters.

Witci (1): That is, one second, come carefully one second is waiting for the keyboard event to do something and finally read a number for me after that.
So-called "his ski code returns
OX means hexmelshel
FF means based on 8
Why do I do this: Depending on what operating system you use, the number that comes back may not necessarily be "8-bit
I say 8 bits of the last 27
If you hit the ESP key from this infinite ring, and close the windows.
So what is the output here?
The more I increase this front number, the more I wait to show the results at the output.

Binary image processing on images that have been converted to only 0 are only 255 are not gray and Black & White.


Binary Pictures: There is no gray surface between their
Binary Declaration Analysis: Any extension that leads to the production of a binary image or creates an operation on that binary image that can be 0: Pixel and 1: Pixel Being.
One of the things that can be done is Part Inspection in the industry

In the rail they have pills, we can discover the empty pill in binary images.
When I write a role on paper, it doesn't matter how bolder or bold it is.
Being or not being in that role is important

The settings we want to read here are yellowing, that is, I can know what the original image is by binary.
I need some places to count the pixels or some of the patterns I have in that image.
There is time to come together, even if there is noise, I have to be able to seek it.
Whether or not to separate these, or finally what the fits are, what looks like, some of these features.

### Example: Blood cells
There are still things in these laboratories where when the average is given with a microscope starting from an area to count the cells, and these cells are healthy if they have a standard number, and if it is less or more, it may be one. Alert for a particular illness that we can fully human, may have problems, for example, because of some cells' noise
Here I have a few Celleles who are interconnected and I can have pre-processes here to do this according to binary operations, in which these cells are interconnected or the cavity that falls between them. To.
We have Pepper noise (salt and pepper noise) when I have a white dot in the unintended black image, and when there are several black spots on the backdrop, it is like a pepper that is poured on the photo and I should be able to be able to do so. In this operation we read, I am actually usury or resistant.
The use of use of this module will be a trick scale images that make them a suitable threshold to black and white decisions, for example, if Wali was above 127, and if below 127, it would be black -so it would be black -thus black Do we turn our decisions from the gray surface to the surface of the white, and what the right sour holder to what we have?
This limit was just an example of 127. We need to be able to examine those components that need to be separated or separated for specific reasons, and finally, the types of extruders we can have as operations on binary images.


### A threshold or binary image of the image in Open CV:
Open CV has implemented us with the relents it provides for us.
The first thought: a simple trick that we can say to binary images so that if the point we have about our image was bigger than a threshold, the click of the Wali Wali was brought to it, and finally 0 Leave.

The X axis listed all the pixels of the image.
For each pixel of this gray image, we have that pixel, for example 0, 100 and 255
This blue line: the threshold limit or the so -called "we have"
If pixel was above this threshold (turning it into a maximized amount)
And if the pixel was below this threshold, turn it into 0 as you can see in the figure above.
On the two we have in the figure: The binary is an inverted.

In fact, the opposite is the case, with the exception that if I had passed the threshold, I would black out that pixel, otherwise I would make it white or Max Valio instead of black.

Third mode: Tranci is. From the top to the top, it does not touch us and does not touch the bottom.

For every single rows and columns you have for this image, you will do the review that Gary Skille gets your hand if that pixel was above the threshold. Put the previous one and don't give up on it/
Finally, we have a zero -shawl, which kills the subsidiaries and holds the top of the trick, and we can say that if that pixel was more than our Austan, do not give up, and if it was below the threshold, That hold the top of the blue line and under the blue line it was 0/0/

Below: We can have the underwear, which is the opposite of the image above. We cut the top 0 and otherwise we take 0.
I first loaded the image to show the output.
Actually the image of a gradient that turned from black to white

I will do this with the beginning of the work.
But we want to have Open CV images with ourselves.
I loaded a picture here.

Ret is the same trick that was chosen

In the slides, we examined 5 methods.
We mentioned here.
See what effect each of these has on my output,
To have a more productive vision or sensation and understand more about what this crackdown is. On a picture of a car license plate
And I just got the same code above by changing the input photo:


I loaded an image that is a car license plate. The type of window I said would be open.
This is an optional type and you can cut and see its effect.
And I set a basic size for this Windows because my plaque is too small and it didn't leave it, and I had to make the window more likely to have enough places.

My goal is to one of them to make the type of dust, and one of them can determine that threshold for me, and I finally pushed the demo.
That first gets a Wali and I just came first with its 0 Eishelial, and then I change that Calback calls my leak change as a cuban as a cuban because after my modifications, the dinner -so -sour and the type of trick. To have these with Global Keyword: Golbal I could later show my image at the end of my notebook except for the "Yui" that Open CV gives me, as well as the final Waliwi and that method in the notebook. I can print it. I put a whisper when my crack was displayed until a button remains on the screen, and if I hit the next line, go to the next line and all the windows that are open and leave the load.
And if I go back up and see your self, I will give you this pass by changing each leaving, and here I read two of my cracks:
1- What is the abandonment of typing 2- Waliwo's cracks on my specific Windows?
I take the Vali and with the function of the trick I read this image of Gary Skille with the threshold limit I want, for example 100, and so on, and finally typing the threshold that I have examined and passed on. .
I made a list and print every threshold I set, I print its name by passing the Type Typing number.
I can change the type of tricking here.

By setting up the plaque, the plaque is the least -mounted Noise and read all the numbers.


## Image Processing in Python with OpenCV

This text is a guide to basic image processing techniques using Python and OpenCV. It covers reading, displaying, manipulating, and converting images, along with some essential concepts like binary image processing and mouse click events.

**Aims of the Code:**

The code aims to demonstrate various image processing operations, including:

* **Reading and displaying images:** Loading images from files and displaying them in a window.
* **Color space conversion:** Changing the color space of an image from BGR (Blue, Green, Red) to RGB (Red, Green, Blue) and converting color images to grayscale.
* **Pixel manipulation:** Modifying individual pixels within an image to change its appearance.
* **Binary image processing:** Converting images to binary (black and white) and performing operations on binary images, like thresholding.
* **Mouse click event handling:** Detecting mouse clicks on an image and responding to them, for example, drawing shapes at the click location.

**Outcomes:**

The code helps you understand the fundamentals of image processing in Python, including:

* **Reading and displaying images:** Learning how to read images from files using OpenCV and display them using Matplotlib.
* **Color space conversion:** Understanding the differences between BGR and RGB color spaces and how to convert between them.
* **Image manipulation:**  Learning how to modify pixels, convert images to grayscale, and apply thresholding techniques.
* **Mouse event handling:**  Implementing code to detect mouse clicks and respond accordingly.
* **Binary image processing:**  Understanding the concepts of binary images and their applications in image analysis.

**Types of Image Processing:**

The text covers two main types of image processing:

* **Color Image Processing:** Includes operations like color space conversion, pixel manipulation, and applying different color maps.
* **Binary Image Processing:**  Involves converting images to black and white, performing operations like thresholding, and applying techniques for image analysis.

**Key Concepts Explained:**

* **Matrix Representation:** Images are represented as matrices in Python, where each element corresponds to a pixel value.
* **OpenCV:** A powerful library for image and video processing in Python.
* **Numpy Array Slicing:**  Used to access and manipulate specific parts of the image matrix.
* **Color Spaces:**  Different ways to represent color, such as BGR (Blue, Green, Red) and RGB (Red, Green, Blue).
* **Gray Scale:**  A color space with only shades of gray.
* **Thresholding:**  Converting an image to binary by setting all pixel values above a certain threshold to white and all below to black.
* **Mouse Events:**  Events triggered by mouse actions, like clicking or moving the cursor.
* **Binary Images:**  Images composed of only black and white pixels, useful for image analysis and object detection.
* **Salt and Pepper Noise:**  A type of noise that appears
## Understanding the Code and its Goals

This text describes how to use different thresholding methods in OpenCV for image processing. The main goal is to convert a grayscale image to a binary image (black and white) by setting a threshold value. 

Here's a breakdown of the code and its objectives:

**What the Code Does:**

* **Explains Thresholding Concepts:** The text introduces various thresholding methods, including simple thresholding, inverse thresholding, adaptive thresholding, and Otsu's thresholding.
* **Illustrates Thresholding Techniques:** It demonstrates how to apply these methods in OpenCV using Python, showing the effect of each method on a sample image.
* **Applies Thresholding to a Real-World Example:** The code is applied to a car license plate image to highlight its use in real-world scenarios.
* **Provides User Interaction:** The code allows users to interactively adjust the threshold value and see the results in real-time.

**Aims of the Code in Python:**

* **Demonstrate Thresholding Methods:** The code aims to provide a practical understanding of different thresholding methods and their implementation in OpenCV.
* **Simplify Image Segmentation:**  Thresholding is a fundamental technique used for image segmentation, separating different objects or regions within an image.
* **Enhance Image Features:** Thresholding can be used to emphasize certain features within an image, making them easier to identify and analyze.
* **Prepare Images for Further Processing:** Binary images resulting from thresholding are often used as input for other image processing tasks, such as edge detection and object recognition.

**Outcomes:**

* **Understanding of Thresholding Techniques:** The code helps understand the principles of different thresholding methods and their applications in image processing.
* **Practical Implementation in OpenCV:** The code provides practical examples of applying these techniques in OpenCV using Python.
* **Ability to Implement Thresholding for Image Processing:** The user will be able to implement thresholding techniques for various image processing tasks.
* **Improved Understanding of Image Segmentation:** The code helps understand how thresholding plays a crucial role in image segmentation, a key aspect of computer vision.

**Types of Thresholding Techniques Covered:**

* **Simple Thresholding:** Sets all pixel values above a certain threshold to white and all below to black.
* **Inverse Thresholding:** The opposite of simple thresholding, setting values below the threshold to white and above to black.
* **Adaptive Thresholding:** Calculates the threshold dynamically for different regions of the image.
* **Otsu's Thresholding:** An algorithm that automatically finds the optimal threshold value for separating foreground and background in an image.

**Overall:** This code provides a valuable introduction to thresholding techniques in OpenCV, enabling users to understand and implement these methods for image processing tasks.

