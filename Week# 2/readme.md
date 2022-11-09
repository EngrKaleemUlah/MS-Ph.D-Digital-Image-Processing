In this week the basic operations are performed on image e.g reading image with openCV. (--> 0 in reading is for grayscale).
after the image has been read the pixel values of the image are shown as a table. (image is resized just to fit the table on the screen).
The image has resized manually and the approach used is even-rows and columns. For each iteration we have taken only the even rows and columns of the image.
The image is reduced to different sizes, from 512, 256, 128, 64, 32.
The first loop in the resizing cell traverses the rows while the inner loop is for columns of the image.
Pixel replication is the technique for upsampling (zooming) the image. it is just repeating the rows and columns to fill up the imaginary grid.
Quantization of image means how larger the range of information an image contains. We have generated slices which represents information of a specific bit level, i.e
8-bit will contains all the iformation from 0-255 but what if we omit the other 7-bits.. for this we just considered only those values which stores information of 8th-bit
which are >127 to 255.
