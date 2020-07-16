### Table of Contents

  1. [Installation](#installation)
  2. [Project Motivation](#motivation)
  3. [File Description](#files)
  4. [Results](#results)
  5. [Licensing, Authors, and Acknowledgements](#licensing)
  
## Installation <a name = "installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

# Project Motivation <a name = "motivation"></a>
This project analyzes disaster data from Figure Eight to build a model for an API that classifies disaster messages. Natural Language Processing methods are used to clean the data. There are three componenst of this projects:
1. ETL pipeline
2. ML pipeline
3. Flask web app

## File Description <a name = "files"></a>

* `process_data.py` is a python script that containts the data cleaning pipeline.

* `message.csv` contains original messages received during a disaster, and the `categories.csv` contains the categories of each message. 

# Results <a name = "results"></a>

## Licensing, Authors, and Acknowledgements <a name = "licensing"></a>

Thanks to Figure Eight Inc. for the data. 
