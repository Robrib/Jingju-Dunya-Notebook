# Jingju-Dunya-Notebook

## Description

This repository contains a docker-compose file to run a Jupyter server and the notebook to download and analyse data and metadata from the Jingju Corpus of Dunya(http://dunya.compmusic.upf.edu/). 

## Installation

### Windows
https://docs.docker.com/docker-for-windows/install/

### Mac
https://docs.docker.com/docker-for-mac/install/

### Ubuntu
https://docs.docker.com/engine/installation/linux/docker-ce/ubuntu/#install-docker-ce

## Run
In a terminal/console window, change to this directory

On MacOS or Windows, run:

    docker-compose up

On Linux, run the following (this command ensures that any files you create are owned by your own user):

    JUPYTER_USER_ID=$(id -u) docker-compose up

Then accesss http://localhost:8888 with your browser and when asked for a
password use _mir_

Then, you can access the notebooks from the browser and run them.

## Credits
This work is based on a collaboration between Honglin Ma, Rafael Caro Repetto, Rong Gong, Alastair Porter and Xavier Serra. The notebook use the Jingju Corpus in Dunya(http://dunya.compmusic.upf.edu/).






