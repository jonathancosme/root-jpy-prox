# Base Jupyter Notebook with root/sudo capabilities (Python 3.8)

This is a version of the [jupyter/base-notebook](https://hub.docker.com/r/jupyter/base-notebook/) image that allows users to pass sudo commands (passwordless) in the terminal of jupyter lab, with Python 3.8 installed by default.

This image is publicly available here:  
[jonathancosme/base-notebook-root](https://hub.docker.com/repository/docker/jonathancosme/base-notebook-root-py38)  

The original (unmodified) files can be found [here](https://github.com/jupyter/docker-stacks/tree/main/base-notebook)

The code is almost identical except for three slight modifications:

modification 1 is in **Dockerfile**:  
![](images/image_1.png)  

modification 2 is in **Dockerfile** file:
![](images/image_4.png)   

modification 3 is in **start.sh** file:
![](images/image_2.png)   
  
and you should be able to run sudo commands in the terminal  
![](images/image_3.png)  
  