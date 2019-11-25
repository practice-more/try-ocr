# try-ocr
have a try with ocr


# tesseract

## Install

https://github.com/tesseract-ocr/tesseract/wiki

### linux

```
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
sudo apt install tesseract-ocr-chi-sim
```

### windows

windows
https://github.com/UB-Mannheim/tesseract/wiki

Installer for Windows for Tesseract 3.05, Tesseract 4 and development version 5.00 Alpha are available from Tesseract at UB Mannheim. These include the training tools. Both 32-bit and 64-bit installers are available.
An installer for the OLD version 3.02 is available for Windows from our download page. This includes the English training data. If you want to use another language, download the appropriate training data, unpack it using 7-zip, and copy the .traineddata file into the 'tessdata' directory, probably C:\Program Files\Tesseract-OCR\tessdata.

## cmd test

```
tesseract test_p2.png out_pic -l eng+chi_sim 


tesseract test_en_chi_sim.png out_en_zh -l eng+chi_sim 


tesseract test_en.png out_en
```
有时候会提示dpi或者size太小，resize下图片，变大一点就行。
