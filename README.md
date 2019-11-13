# toronto-ml-summit
Examples, demos and exercises of my workshop on jupyter widgets at [Toronto ML Summit](https://torontomachinelearning.com/events/#workshops)

The provided Dockerfile can be used to build a docker image (assuming docker is already installed) and launch the Jupyter notebook. 

Command to build the image:

    docker build -t jupyter_widgets:v1 .

Command to run the Jupyter notebook:

    docker run -p 8888:8888 -v "$PWD":/home/jovyan jupyter_widgets:v1
