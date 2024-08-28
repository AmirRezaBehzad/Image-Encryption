# Image Encryption Using SEA
This repository contains Python code to encrypt images using the SEA (Shuffle Encryption Algorithm) [based on this paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=6de8e8ce6fbb07491a331521abb28c3a101577f1).
## Features :
  - Convert an original image to grayscale.
  - Encrypt the grayscale image using the SEA algorithm.
  - Display the original image, grayscale image, and encrypted image side by side.
  - Calculate and plot histograms for the grayscale and encrypted images.
## REQUIREMENTS :
  - python 3
  - cv2 module
  - matplotlib.pyplot
  - matplotlib.image
  - numpy
  - re

## Algorithm Review:
### Introduction:
The Shuffle Encryption Algorithm (SEA) is a symmetric encryption technique designed for image encryption. It operates by shuffling the pixels of an image based on a user-defined encryption key, thereby rendering the encrypted image unintelligible without the corresponding decryption key.

### Key Features:
#### 1. Symmetric Encryption: SEA employs symmetric encryption, meaning the same key is used for both encryption and decryption.
#### 2. Pixel Shuffling: The algorithm shuffles the pixels of the image according to the encryption key, enhancing security by introducing randomness.
#### 3. Substitution: SEA substitutes pixel values using a randomly generated S-box, further obscuring the encrypted image.
#### 4. Bit Manipulation: The algorithm performs bit-wise operations to encrypt the image, providing additional security layers.

### Usage Guidelines:
#### 1. Input Image: Provide the path to the image you want to encrypt.
#### 2. Encryption Key: Enter a series of integers in the format (M1, M2, M3, ..., Mn) as the encryption key. These integers determine the bit positions for pixel shuffling.
#### 3. Output: The script generates the encrypted image and displays it alongside the original and grayscale versions of the input image.

### Conclusion:
This script offers a straightforward approach to encrypting images using the Shuffle Encryption Algorithm. By following the provided guidelines and understanding the algorithm's key features, users can secure their images against unauthorized access. However, it's important to note that while symmetric encryption techniques like SEA provide confidentiality, they may not offer the same level of security as more advanced cryptographic methods for sensitive data. Users should assess their security requirements and consider additional measures accordingly.

## Usage Example:
[Original Image](Original_Image.png)

[Grayscale Image](Grayscale_Image.png)

[Encrypted Image](Encrypted_Image.png)

> [!NOTE]
> If you want to run this code first you have to upload this picture into your google colab: [SpiderMan.jpg](SpiderMan.jpg).

> [!NOTE]
> If you wish to use any other images, please upload your desired image to your Google Colab environment and then update the image link within the "image_path" variable accordingly.
