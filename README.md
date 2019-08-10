# LearnOCR

The following is documentation on LearnOCR, an optical character recognition algorithm build on TesseractOCR for the purpose of converting SEC Examination Papers into text documents. There is also documentation on hardcoding images into these text documents.

## Pre-init of LearnOCR

There are numerous dependancies required to use this software. Some of them relate to TesseractOCR, and some of them relate to the interpretation of PDF files.

The following are the dependacies that need to be satisfied before initialising the software:

<code>
Python 3.7 or higher, 
  libtesseract (A language wrapper for Python for TesseractOCR), 
  pyocr, 
  Poppler (And its many, many automatically installed dependacies), 
  PDF2Image
</code>

The last two entries can be found at https://simply-python.com/2018/11/15/convert-pdf-pages-to-jpeg-with-python/, the rest will turn up in a quick google search of their names.

## Using LearnOCR
