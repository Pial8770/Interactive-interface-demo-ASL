In order to run the interactive demo the following sequence needs to be followed:
1. Create a folder name "background_images" in Google Drive and upload environmental images in that folder.
2. Run "thesis_extended_test_set_creation_final.ipynb"
3. Run "thesis_SLTUNET_ASL_final.ipynb"
4. Run "thesis_YOLOv8_ASL_final.ipynb"
5. Run "thesis_VGG19_ASL_final.ipynb"
6. Run "thesis_interactive_demo.ipynb"

It is recommended to run the codes using Google Colab platform as the codes were originally written and executed there.




Another way of accessing the interface is by downloading the trained models and running only the "thesis_interactive_demo_final.ipynb" file on Google Colab.

Steps:
1. Download the trained models:
You can download the trained models from below links:
VGG19: https://drive.google.com/file/d/1olEhKrpeJ2GbIhAuNQeephWEZPtNNewD/view?usp=sharing
SLTUNET: https://drive.google.com/file/d/1iVmy0t7YWP5rMgT1TXImIDpU2yKzyLWm/view?usp=sharing
YOLOv8: https://drive.google.com/file/d/1qFcLAhiDLIVyhI5KacxEnklHtlRZ3Rii/view?usp=sharing

2. Place the downloaded models in Google Drive.

3. Update model paths:
Update paths to the models in the 4th block of "thesis_interactive_demo_final.ipynb":

#Model paths in google drive
VGG_PATH  = "/content/drive/MyDrive/trained_vgg19_half_split.pth"
SLT_PATH  = "/content/drive/MyDrive/sltunet_final_best.pth"
YOLO_PATH = "/content/drive/MyDrive/best.pt"

4. Create folder in Google Drive for background images:
Create a folder call "background_images" in Google Drive. Keep your desired background images in this folder.

5. Update path to background_image folder in 4th block of "thesis_interactive_demo_final.ipynb":
#Background images folder
ENV_BG_DIR = "/content/drive/MyDrive/background_images"

6. Run all other blocks of code from "thesis_interactive_demo_final.ipynb".

7. At the end, you should be able to play with the interactive demo.



Good Luck!
