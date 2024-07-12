# Text Extraction From Images Application
In this project, we will be working on extracting text from images. After extracting the text we will apply some basic functions of OpenCV on that text to enhance it and to get more accurate results. This project will be very useful as it will save time and effort of typing from an image.We started with learning how to install tesseract which is the used for text extraction. Next we took an image and extracted the text from that image. We learned that we need to use certain image transformation function of OpenCV in order to extract text from complex images.Different organization can use this to extract useful information from the image and store it. Individuals can use it for saving their time and effort for typing. THE STEPS :
1. Step 1 : DOWNLOADING TESSERACT AND INSTALL IT WITH OTHER DEPENDENCIES.
2. Step 2 : LOADING THE IMAGE FOR TEXT EXTRACTION, RESIZING IT, AND THEN SAVE IT.
3. Step 3 : USING PYTESSERACT TO EXTRACT THE TEXT FROM THE IMAGE.
4. Step 4 : PROCESSING THE NEXR EXTRACTED FROM THE IMAGE.
5. Step 5 : USING COMPUTER VISION FOR FURTHER PROCESSING OF COMPLEX IMAGES.
6. Step 6 : REMOVING NOISE FROM THE IMAGE USING THE BLUR FUNCTION.
7. Step 7 : PERFORM THRESHOLD TRANSFORMATION OF THE IMAGE.
8. Step 8 : USING ERODE FUNCTION OF CV2 ON IMAGE.
9. Step 9 : PERFORMING SOME OTHER IMAGE PROCESSING OPERATIONS.
10. Step 10 : DRAWING RECTANGLES AROUND A ACHARACTER AND A PARTICULAR PATTERN/WORD.

# Step to Run Application Locally
1. Step 1 : create the copy of the project.
2. Step 2 : open command prompt and change your current path 'app.py' file.
3. Step 3 : create environment by command given below - conda create -name <environment name>.
4. Step 4 : activate environment by command as follows - conda activate <environment name>.
5. Step 5 : install tesseract using windows installer available at : https://github.com/UB-Mannheim/tesseract/wiki
6. Step 6 : note the tesseract path from the installation. Default installation path at the time of this edit was : C:\ProgramFiles\Tesseract-OCR. It may change so please check the installation path.
7. Step 7 : pytesseract.pytesseract.tesseract_cmd = r'C:\ProgramFiles\Tesseract-OCR\tesseract.exe'
8. Step 8 : use command below to install required dependencies- python -m pip install -r requirements.txt
9. Step 9 : run application by command- python app.py
10. Step 10 : you have sample_data folder where you can get images to test.

