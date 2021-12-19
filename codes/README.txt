Group ID : B21PV04
--------------------------------

There are 3 folder in this directory named "colab notebook files", "model designs", "python files".
Folder "colab notebook files" contains code in the form of ".ipynb".
Folder "python files" contains code in the form of ".py".
Folder "model designs" contains the pictures of the models used.

Our project primary dataset is NTIRE 2020 dataset. To run the project first we have to download the NTIRE 2020 (25gb). Then we have to resize the each 
RGB and Spectral Image from 512x512x3 to 256x256x3 using preprocessor.py.
It contains 2 tracks, "clean" and "real world". Total of 450 training images, 10 validation images, 10 test images.

Our 3 models files are "btp_original.py", "btp_original_with_hyperoptim.py", "res_net.py". We have to change the dataset paths in these files.
Each model file is stand alone they dont require any other files to be imported. After changing the path of dataset we are go to with training of the models.

"btp_original.py" and "btp_original_with_hyperoptim.py" will take longer time run comparing to "res_net.py" so it recommended to run on GPU.
You can change the hyper parameters like learning rate and epochs to test according to your resources.