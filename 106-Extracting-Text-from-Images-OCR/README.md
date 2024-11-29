## Install Tesseract Locally

The installation requires a few steps:

1. First, we need to install the C++-based engine [Tesseract](https://tesseract-ocr.github.io/tessdoc/Installation.html). You can find some installation guides for different operating systems in the [Tesseract documentation](https://tesseract-ocr.github.io/tessdoc/Installation.html). If you are on a Windows system, you can use the [Windows installer](https://github.com/UB-Mannheim/tesseract/wiki) provided by the University Mannheim.

2. To use the engine in Python, we are using the library [pytesseract](https://pypi.org/project/pytesseract/), which is a wrapper for [Tesseract](https://tesseract-ocr.github.io/tessdoc/Installation.html).

3. On top of that, we are using [pdf2image](https://pdf2image.readthedocs.io/en/latest/installation.html), which converts PDF to a PIL Image object.

4. To use [pdf2image](https://pdf2image.readthedocs.io/en/latest/installation.html), we need to make sure the _poppler_ library is installed on our machine. You can find a brief installation guide for _poppler_ within the [pdf2image documentation](https://pdf2image.readthedocs.io/en/latest/installation.html). 