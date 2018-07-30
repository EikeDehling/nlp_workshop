# NLP Workshop

In this workshop we'll show some basic language processing tehniques, especially text classification


## Running

To run the notebook environment, use either of the commands below, depending on if you have docker or python installed.

```
docker run -it --rm --user root -e NB_UID=1000 -e NB_GID=1000 -v `realpath .`:/home/jovyan/work -p 8888:8888 jupyter/datascience-notebook
```

Alternatively you can setup a python virtual environment, install the required packages in there and run:

```
virtualenv .
bin/pip install -r requirements.txt
bin/jupyter notebook
```
