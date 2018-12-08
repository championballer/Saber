# pdftotimetable
An image processing software which exports timetable

Should contain an OCR for detecting text in PDF page. The detected text should then be outputted accordingly setup in excel file in proper table format. 

1. OCR : Stage1: OCR framework in python, Stage2:self implemented using deep learning 
2. Formatting the recognised text as per requirements and outputting it an excel sheet or the required format.

Features :
1. Might contain an option to ignore certain text based on the input by the user. 
2. Color coding based on core, discipline centric and generic electives.
3. Check for clashes(if multiple images are inputted)

Dataframe output post array making from recognised text. 

Assumption : The input image/pdf should be well edited and in monochrome and should have a table(_the timetable_) that is to be recognised.
