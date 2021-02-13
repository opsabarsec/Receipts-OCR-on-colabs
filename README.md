# Receipts-OCR-on-colabs: Pytesseract vs. EasyOCR.

In this notebook I have run both packages on images downloaded from 
https://expressexpense.com/large-receipt-image-dataset-SRD.zip

Pytesseract runs well just using CPU but often does not produces accurate outputs due to focus/shadows issues of the original image.
I have tried preprocesing using OpenCv but that helped moderately.

Better results using EasyOCR library. It requires GPU accelerated environment though and runs smoothly when this is activated in a Colabs notebook.

