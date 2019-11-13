# toronto-ml-summit
Exercises, examples and demos of my workshop on jupyter widgets at [Toronto ML Summit](https://torontomachinelearning.com/events/#workshops)

The provided Dockerfile can be used to build an image and launch the Jupyter notebook. 

Command to build the image:

    docker build -t jupyter_widgets:v1 .

Command to run the Jupyter notebook:

    docker run -p 8888:8888 -v /Users/ccherukuri/projects/toronto-ml-summit:/home/jovyan/work jupyter_widgets:v1
