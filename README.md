# etl-pipeline
## Introduction

This code contains the steps to build an ETL pipeline that carries out the following tasks:
* Extracts transactional data from a local database
* Identifies and removes duplicates
* Loads the transformed data to s s3 bucked

## Requirements

The minimum requirements:
--Python 3+

## Step by Step

* First please contact me to get the copy of the database and update the file path accordingly
* Clone the repository, and change the directory to **etl-pipeline**: 

git clone https://github.com/Estheryunn/etl-pipline.git

git pull
* Install the libraries that you will need to run main.py

Mac users:

pip3 install -r requirements.txt

Window users:

pip3 install -r requirements.txt
* Copy the .env.copy file to .env and fill out the environment variables.
* Run the main.py script

Mac users:

python3 main.py

Window users:

python main.py