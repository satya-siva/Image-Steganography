This repository describes the implementation of Image steganography using python programming language.Steganography refers to the process of hiding a secret message within a larger one in such a manner that someone 
cannot know the presence or contents of the hidden message. The objective of Steganography is to maintain secret communication between two parties. Unlike Cryptography, where we can conceal the contents of a secret 
message, Steganography conceals the fact that a message is transmitted. Even though Steganography differs from Cryptography, there are various analogies between the two. There are many types of steganography process 
includes Text Steganography,Image Steganography,Video Steganography,Audio Steganography,Network Steganography and E-mail Steganography . In this repository I have implemented the Image steganography using the python
programming language.
Image Steganography is hiding information within images such that it deceives the viewer as if there is no hidden information within the image. With the help of this, two people can communicate secretly.
Steps:
1. Importing modules . PIL module is imported to extract Images and work with images.
2. Taking an input to know whether what to encode or decode the image.
3. If selected for the encode:
   Read the input image with extension.
   Read the data to be encode into the image .
   Performing the encoding operation (modifing the pixels in the image as the ASCII values of the data)
   Read the input name to store the encoded image with extension.
4. If selected for the decode :
   Read the unput image with extension to decode.
   Performing the decode algorithm to get the encoded information or message.
