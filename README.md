# Image Distance Plot Viewer

Matlab App to view zoomed in versions of the plot and images.

## Data Format
The data file to be imported should have the following format:
- x: 1xn vector of x-coordinates (0-1)
- y: 1xn vector of y-coordinates (0-1)
- s: 1xn vector of image size (0-1)
- imName: 1xn cell array of image names (eg. {'a.png' 'b.png' 'c.png'})
- imPath: 1xn cell array of image paths (eg. {'~/Desktop/imFolder' '~/Desktop/imFolder'})

## Random Data
Select the random data option in the Help menu to play around with the GUI.

## Note
The image border (usually indicates a response of some kind to the image) is assumed to be a part of the image itself. In future versions, I may add a way to import the response with the data and add the image border in the GUI itself.