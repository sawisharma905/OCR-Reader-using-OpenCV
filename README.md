# OCR-Reader-using-OpenCV
This repository contains the code written for making an Optical Character Reader using python and its libraries.

In the OCR reader using OpenCV, I used the Google Tesseract as the OCR engine. I studied about many OCR engines such as Google vision, Amazon Textract, etc., but all of them were paid, so I chose for Tesseract. 
First I imported OpenCV into my notebook to read the images. After that I imported Tesseract, the engine, so that I can convert the text in the image to extracted text. I filled the given template with pen and scanned it to obtain images for analysis. I did two analyses, one with the normal scanned image, and second with the image that is converted into grayscale and the brightness is adjusted.
First I tried with the images that I got on scanning the form with my mobile phone, but the code was not reading the text with much accuracy because the image was not so clear and was too noisy. Then I tried with the scanned images, which gave me better results. Then I tried with the normal image, grayscale image and its brightness enhanced images to see what kind of images give better results. Almost both the methods gave similar outputs, but the data obtained from the normal image was comparatively more accurate.
