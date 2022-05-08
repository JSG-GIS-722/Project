Public GIT repository: https://github.com/JSG-GIS-722/Project.git
Test data which is affected by specific copyright arrangements can be found through this link.
A list of all dependencies used by the project can be found in the requirements file (ctrl + click to open).


The best way to use this ArcGis Notebook (EGM722Classifier.ipynb) is to open it from a new ArcGis Pro project.  Some of the Deep Learning dependencies used in the Notebook require the ArcGIS Image Analyst extension, so a licensed copy of ArcGis Pro needs to be open while running the ArcGis Notebook.  This repository includes the required .yml file to duplicate the python environment, but the before mentioned licensing constrain might still apply.
This project was developed using ArcGis Pro v2.9 with ESRI's Deep Learning libraries 2.9 and a functioning dedicated python environment.  ESRI's Deep Learning libraries are available here.
Hardware-accelerated GPU scheduling is recommended to reduce latency and improve performance when executing processor-intensive Deep Learning algorithms.
The project files are divided in 2 folders, mapped within a "U:" drive created to facility file management.  In this drive, I created a folder called Project for public GIT files, and a ProjectData folder for OSNI-copyright files and intermediate output files.  Users of this ArcGis Pro notebook should replicate this structure or adapt the script accordingly.
The project uses training data obtained from OSNI's own 4-band orthoimagery (with spatial resolution of 40 cm, and red, green, blue and NIR bands).  Training data used in this Notebook needs to be collected using the Label Objects for Deep Learning tool for Imagery Classification, exported  with the Export Training Data feature and saved as a feature class file called trainingsamples.shp in ProjectData.
Finally, this ArcGis Pro notebook creates a significant number of files and folders, and therefore it is necessary to ensure that the device in which it is run has a minimum of 5 GB of memory available).  
