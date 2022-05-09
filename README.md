# AsciArtist
Create a Neural Network that Converts Images to Asci Art

### Pipeline

1.  Image fed to NN
2.  NN converts the image to an M x M grid of keyboard symbols.
3.  Keyboard symbols converted to asci image
4.  Loss function between image and asci image

## TODO

1.  Create a symbol to asci image converter
    1. Get Consolas Regular size 11 font as MNIST images
       1. Create a grid of all characters in Notepad
       2. python slice them into chunks.
    2. Write a program to paste the consolas MNIST images in the manner specified by NN
2.  Find an appropriate loss
