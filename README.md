# lsb_steganography

LSB Steganography

Introduction

This project implements LSB (Least Significant Bit) Steganography, a technique used to hide secret messages within images. By modifying the least significant bits of pixel values, this method enables data to be embedded without noticeable visual changes.

Features

Image Encoding: Efficiently embeds text data into image files.

Image Decoding: Extracts hidden text data from encoded images.

User-Friendly Interface: Simple and intuitive UI for seamless operation.

Error Handling: Ensures reliable encoding/decoding with informative prompts.

Supported Formats: Works with popular image formats such as PNG and BMP.

How It Works

Encoding Process:

The input image is read and processed pixel by pixel.

The text data is converted into binary format.

The binary data is then embedded into the least significant bits of the image's pixel values.

Decoding Process:

The encoded image is processed to extract binary data from the least significant bits.

The binary data is reconstructed back into readable text.

Installation

To set up the project, follow these steps:

# Clone the repository
git clone https://github.com/aayush992/lsb_steganography.git

# Navigate to the project directory
cd lsb_steganography

# Install dependencies
pip install -r requirements.txt

Usage

Encoding a Message

python encode.py --image <input_image> --message "<your_secret_message>" --output <output_image>

Decoding a Message

python decode.py --image <encoded_image>

Example

Encoding:

python encode.py --image sample.png --message "Hello, World!" --output encoded_image.png

Decoding:

python decode.py --image encoded_image.png

Requirements

Python 3.x

Libraries: Pillow, NumPy

Install dependencies via:

pip install pillow numpy

Project Structure

├── encode.py      # Script for encoding messages
├── decode.py      # Script for decoding messages
├── requirements.txt  # List of dependencies
├── sample.png      # Sample input image
├── README.md        # Project documentation

Future Enhancements

Implement encryption for improved data security.

Introduce a GUI for better user experience.

Support additional image formats like JPEG.

License

This project is licensed under the MIT License.

Author

Aayush
