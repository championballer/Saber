# pdftotimetable
An image processing software which exports timetable

Should contain an OCR for detecting text in PDF page. The detected text should then be outputted accordingly setup in excel file in proper table format. https://www.learnopencv.com/deep-learning-based-text-recognition-ocr-using-tesseract-and-opencv/

To get a rough dataframe, Tabula has also been tried out and it is giving useable results.
1. OCR : Stage1: OCR framework in python, Stage2:self implemented using deep learning (https://medium.com/syncedreview/stn-ocr-a-single-neural-network-for-text-detection-and-text-recognition-220debe6ded4)
2. Formatting the recognised text as per requirements and outputting it an excel sheet or the required format.

Features :
1. Might contain an option to ignore certain text based on the input by the user. 
2. Color coding based on core, discipline centric and generic electives.
3. Check for clashes(if multiple images are inputted)

Dataframe output post array making from recognised text. 

Assumption : The input image/pdf should be well edited and in monochrome and should have a table(_the timetable_) that is to be recognised.

# Current situation:

![Checkpoint1](https://raw.github.com/championballer/pdftotimetable/master/Checkpoint1.png)
![Checkpoint2](https://raw.github.com/championballer/pdftotimetable/master/Checkpoint2.png)

