Multimedia-ImageProcessing
==========================

Quantization and Subsampling of images. for YUV processing reasons, you will have to convert the image to YUV space, process your subsampling and reconvert it back to RGB space to show the output to display. Remember that if RGB channels are represented by n bits each, then the YUV channels are also represented by the same number of bits. Sub sampling will reduce the number of samples for a channel. When converting back to the RGB space, all the YUV channels have to be of the same size. However the sampling throws away samples, which have to be filled it appropriately by average the neighborhood values. 