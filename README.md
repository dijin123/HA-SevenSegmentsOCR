# HA-SevenSegmentsOCR
The seven_segments image processing integration allows you to read physical seven-segment displays through Home Assistant. ssocr is used to extract the value shown on the display, which a camera observes.

Notes for Home Assistant Core Installations
ssocr must be available on your system. Check the installation instructions below:

```
apk update
apk add pkgconfig
apk add g++
apk add make
apk add imlib2
apk add imlib2-dev
git clone https://github.com/auerswal/ssocr.git
cd ssocr
make
make PREFIX=/usr install
ssocr --version
```

![WhatsApp Image 2024-10-22 at 12 54 42_5d70d918](https://github.com/user-attachments/assets/21c5a768-a60b-4406-b00d-e865751423f8)
![WhatsApp Image 2024-10-22 at 12 56 01_1605d403](https://github.com/user-attachments/assets/16771c80-fa64-4892-bc25-fd902371eac2)

