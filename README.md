# Number Plate Detection and Text Extraction
## Detect and extract text from number plates using YOLOv5 and EasyOCR.
This project focuses on detecting number plates from images using YOLOv5 and subsequently extracting the text from the detected number plates using the EasyOCR library.

The dataset used for training includes various vehicle images with annotated number plates. YOLOv5 is employed for detecting the number plates, and the EasyOCR library is used for extracting the text from the cropped number plate images.

## Dataset Preparation
- The dataset consists of images of vehicles with annotated number plates.
- The annotations are in YOLO format, which includes the bounding box coordinates for the number plates.
- The detected number plates are cropped from the images and passed to EasyOCR for text extraction.

## Conclusion
This project demonstrates a robust approach to detect and extract text from number plates using a combination of YOLOv5 and EasyOCR. The YOLOv5 model is responsible for accurately locating the number plates in images, while EasyOCR efficiently extracts the textual information from the cropped number plates.

## Limitation
The accuracy of text extraction may vary based on the quality of the number plate images and the clarity of the text.
Detection of very small or partially obscured number plates might not be accurate
