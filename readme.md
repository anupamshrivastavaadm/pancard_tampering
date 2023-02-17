This is a Python code for a computer vision project that aims to detect tampering of PAN cards. It works by comparing an original image of a PAN card to a user-provided image, and computing the structural similarity index (SSIM) between the two images to determine their similarity. The lower the SSIM score, the less similar the images are. The code uses the OpenCV library to read, resize, and convert images to grayscale. It also uses the scikit-image library to calculate SSIM, and the PIL library to open, save and display images. Finally, it applies the threshold function and finds contours to identify differences between the two images, and draws bounding boxes around them.

Step to run application:

Step 1:	Create the copy of the project.

Step 2: Open command prompt and change your current path 
to folder where you can find 'app.py' file.

Step 3: Create environment by command given below-
conda create -name <environment name>

Step 4: Activate environment by command as follows-
conda activate <environment name>

Step 5: Use command below to install required dependencies-
python -m pip install -r requirements.txt

Step 6: Run application by command;
python app.py
You will get url copy it and paste in browser.

Step 7: You have sample_data folder where you can get images to test.
