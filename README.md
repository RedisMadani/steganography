# Image Steganography

This project encompasses two algorithms, namely LSB and DCT, designed to embed secret information within images while remaining imperceptible.

**LSB** algorithm inserts the message into the least significant bit of each pixel.

**DCT** algorithm inserts the message into the middle frequency components.

## Requirements

Installation:

```shell
$ pip install -r requirements.txt
```

## Usage

To execute the LSB algorithm:

```shell
$ python3 lsb.py
```

To execute the DCT algorithm:

```shell
$ python3 dct.py
```
