# Image-Recognition-
Introduction 
The Fashion-MNIST dataset is a dataset of Zalando articles’ images. It is composed of 70000 grayscale images of different fashion products, and their correspondent labels. For each category of fashion item there are thousands of images.

Prerequisite 
In order to run the code necessary for this coursework, you need to install the following packages inside a virtual environment. 

Please read this blog for an easy and brief introduction to working with virtual environments: 
https://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/ 

After you finish reading this, create a virtual environment by following these commands
• mkdir my_ML_CW        (create the directory where you will place your code. Copy and paste CW_START.py to this directory) 
• cd my_ML_CW             (go to the created directory) 
• virtualenv env            (this will create a virtual environment called env) 
• source env/bin/activate (this will activate the env environment) 
Now you will see: (env) print in your terminal, it means you are now working from inside the virtual environment called env. That is when you install a python packages (example: pip install numpy==1.15.2), the package will only be accessible when you have the virtual environment activated (so it does not create any conflict with other packages and versions installed system 
wide). 
Now in your python code you can do for example: import numpy, and use the package numpy that you just installed. To exit (i.e. deactivate) the virtual environment, simply run: deactivate, in your terminal). 

Now, make sure  that you have your virtual environment activated (source env/bin/activate), then install the following packages by running these commands one at a time and in this order: 
• pip install numpy==1.15.2 
• pip install sklearn  
• pip install matplotlib==2.2.3 
• pip install tensorflow==1.5 
• pip install keras==2.2.4
Once the installation is completed, run the provided Python script “CW_START.py”, which will display the first 20 images and labels of the datase
