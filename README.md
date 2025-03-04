# capstone-project-2024-t3-3900-W15A_CELERY

This project converts a series of images into an objects and then generates scenes from that object.


# Installation Guide

## Requirements
Before installation note we highly recommend 8GB or more of RAM and 4GB or more of GPU memory. The software was developed and tested on Python 3.10.11 on Windows although any version of Python 3.10 should work as well as any Linux distributions. If the user wishes to make use of any of the camera features they must have an Intel RealSense compatible camera.


## Clone Repository
Firstly, clone the Git project into your chosen directory:
```cmd
git clone https://github.com/unsw-cse-comp99-3900/capstone-project-2024-t3-3900-W15A_CELERY.git
cd capstone-project-2024-t3-3900-W15A_CELERY
```

## Activate Virtual Environment (Optional)
We highly recommend using a python virtual environment. This can be enabled in your root directory as follows:

```cmd
python -m venv .venv
source .venv/bin/activate
```

## Install Dependencies
Install dependencies running the following command in your terminal. 
```cmd
pip install -m requirements.txt
```

# Running 
To run the application, use the command:
```cmd
python src/app.py
```
