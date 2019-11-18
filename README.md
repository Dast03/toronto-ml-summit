# toronto-ml-summit
Examples, demos and exercises of my workshop on jupyter widgets at [Toronto ML Summit](https://torontomachinelearning.com/events/#workshops)

The provided Dockerfile can be used to build a docker image (assuming docker is already installed) and launch the Jupyter notebook. 

Instructions to set up the environment and run the jupyter notebook:

* Build the docker image

`docker build -t jupyter_widgets:v1 .` (don't forget the dot at the end!)

* Start the notebook server

`docker run -p 8888:8888 -v "$PWD":/home/jovyan jupyter_widgets:v1`

* Access notebooks using the following link

`http://localhost:8888`
