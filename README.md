# Segnet-basic
Deep Convolutional Encoder-Decoder Architecture for Semantic Pixel-wise Image Segmentation

Segnet = (Encoder + Decoder) + Pixel-Wise Classification layer

SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation (Vijay Badrinarayanan, Alex Kendall, Roberto Cipolla, Senior Member, IEEE) arXiv:1511.00561v3

What is SegNet-Basic?

"In order to analyse SegNet and compare its performance with FCN (decoder variants) we use a smaller version of SegNet, termed SegNet-Basic , which ha 4 encoders and 4 decoders. All the encoders in SegNet-Basic perform max-pooling and subsampling and the corresponding decoders upsample its input using the received max-pooling indices."
Basically it's a mini-segnet to experiment / test the architecure with convnets, such as FCN.

Example;
Let us take a simple scenario of analyzing an image. Let us assume that your input image is divided up into a rectangular grid of pixels. Now, the first layer abstracts the pixels. The second layer understands the edges in the image. The Next layer constructs nodes from the edges. Then, the next would find branches from the nodes. Finally, the output layer will detect the full object. Here, the feature extraction process goes from the output of one layer into the input of the next subsequent layer.
TO DO: 
 SegNet-Basic
 SegNet
 Test Accuracy
 Requirements
