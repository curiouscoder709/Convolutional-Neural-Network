# Convolutional-Neural-Network

The following codefile has an application of a Convolutional Neural Network with a basic examples of how following methods in it work like - 

1) Stride - Stride determines how many squares or pixels our filters skip when they move across the image, from left to right and from top to bottom.
  
2) Padding - Padding in CNN refers to the addition of extra pixels around the borders of the input images or feature map. This process removes aggregation bias from 
             the convolution operation.
   
3) Maximum Pooling - Max pooling is performed on the convolutional layers of a CNN. It involves sliding a window (often called a filter or kernel) across the input 
                     data, similar to the convolution step, but instead of performing a matrix multiplication, max pooling takes the maximum value within the window.
   
4) Average Pooling - Average pooling computes the average of the elements present in the region of feature map covered by the filter. Thus, while max pooling gives 
                     the most prominent feature in a particular patch of the feature map, average pooling gives the average of features present in a patch.
   
5) Flatten -  It acts as a bridge between the convolutional/pooling layers, which extract spatial features, and the fully connected layers, which perform 
              classification or regression tasks.
