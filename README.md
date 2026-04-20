# mini-rag

this is the minimal implementation for a mini rag application for question answering

## requirements

- python 3.8 or later 

### installing mini-conda

- download and install mini conda from here (https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe)

- create conda environment using this command:
``` bash
$ conda create -n mini-rag-app

```
- activate this conda environment using this command:

``` bash 

$ conda activate mini-rag-app

```
## installation

### installing the required packages

``` bash
$ pip install -r requirements.txt

```

### setup the environment variables

```bash 
$ cp .env.example .env
```

## run the fastapi server 
``` bash
$ uvicorn main:app --reload --host 0.0.0.0 --port 5000

``` 

