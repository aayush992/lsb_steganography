# lsb_steganography

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


Aayush
