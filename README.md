# Data Modeling With Apache Cassandra
 Project repo for the Udacity Data Engineering Program Project 1B.

 This README file includes a summary of the project, how to run the Python scripts, and an explanation of the files in the repository.

 ## Getting Started
1.  The project is run entirely from a Juypter Notebook file.  Open the .ipynb **Project_1B**.

## Prerequisites
1.  Baseline configured Apache Cassandra database.

2.  The following Python libraries need to be installed in the environment.
    * cassandra
    * pandas

    ## Purpose
    The purpose of this database is to conduct ETL operations and store data from user activity from the Sparkify app.  
    This data will be used by the Sparkify analytics team will use this data gain a greater understanding of user activity and songs being listened to.

    ## Dataset

    The dataset is comprised of user names, artist names, songs, for each session and item in each session.

    The data in the CSV is comprised of the following columns and datatype:

| Field                     | Data Type  |
 |------------------------  | ---------- |
| artist                    | text       |
| firstname                 | text       |
| gender                    | text       |
| item number in session    | int        |
| last name of user         | text       |
| length of the song        | float      |
| level (paid or free song) | text       |
| location of the user      | text       |
| sessionId                 | int        |
| song title                | text       |
| userId                    | int        |

Below is a screenshot of the csv

![top five](./images/image_event_datafile_new.jpg)
