Face Recognition

Install first the needed libraries in python using pip installer

input this to your cmd

pip install opencv-python
pip install os-sys
pip install numpy

and download the Haarcascade_frontalface_default file

put the Haarcascade_frontalface_default in the same location of the python files.

If you download the zip file, and extract it on specific folder.
Add a blank folder named "datasets" which will be the datasets for the model.
Add another folder named "your_model" inside datasets folder.


File Tree
Face_recognition folder

        datasets folder:         #inside Face_recognition folder
        example "Jonathan"       #data folder for Jonathan
        
        This python file is inside the face_recognition folder 
        create_data.py            #first time getting data from user
        face_recognize.py         #program recognition when there is data on folder
        haarcascade_frontalface_default.xml
       
        
        
        
