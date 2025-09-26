# Stretch
HTML/javascript utility that seamlessly stretches 2:3 images to fit 4:5 instagram post size.

## How does this work
On the top of the page, a file picker allows you to select a file. This file is expected to be a 2:3 ratio (common ratio from digital cameras). Two slider allows you to fine tune left and right portions of the image that would get streteched to fill the 4:5 ratio while keeping the image height the same.

The bigger part of the image is selected the less stretching and more smoother outcome is achieved. The sliders allows you to find a spot where no important part of the image subject is distorted.

Once you're done, you can click the *Download image* and the page returns the modified image as a png file with some unique name derived from a timestamp.

## Some background

### Motivation
I am an avid portrait photographer shooting a mirrorless camera with 3:2 output. When taking pictures, I don't frame for 4:5 so when it comes to posting to IG, the 4:5 sometimes results in vital parts of the photo being cut off. Rather than cutting vital parts, I would stretch a non vital parts horizontaly. When taking a whole body picture, the sides are often some blurred or studio background or something, where the strech it not at all noticeable.

### Expected usage
The reason why the file selection is not drag and drop is to be compatible with mobile phone file pickers.
