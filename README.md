# mini-rag
This is a minimal implementation of the RAG model for question answering

## Requirements 
python 3.13 or later 

#### install python using miniconda

 1) Download and install miniconda from here : (https://www.anaconda.com/docs/getting-started/concepts/anaconda-or-miniconda#quick-command-line-install)
 2) create a new environment using the following command :
 ```bash
 $ conda create -n mini-rag python=3.13
 ```
 3) Activate the environment :
 ```bash
 $ conda activate mini_rag
 ```



#### (Optional) Setup you command line interface for better readability
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```

## Installation

### Install the required packages

```bash
$ pip install the required packages
```

### setup the environment variables

```bash
$ cp .env.example .env
```
set your environment variables  in the '.env' like 'OPEN_API_KEY' value