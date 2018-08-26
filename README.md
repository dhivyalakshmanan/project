# project
# Logs Analysis

## About
In Full Stack web Developement Log Analysis is the final project, we will work with large amount data across a large database,For this project we need to write python code and sql queries to retrive some data.
## To Run
#### Things we need
* Virtual Machine
* Vagrant
* Python 3
* Git Bash

## Set up
* Install VirtualBox,Vagrant,Python,Git Bash
* Download  fullstack-nanodegree-vm repository.
* Download the newsdata folder
* Unzip the folder and extract newsdata.sql
## Commands To Run
1.```vagrant --version``` : To check whether vagrant is installed or not
2.```vagrant up``` : To bring the Virtual Machine online
3.```vagrant ssh``` : To log on to virtual machine
4.```psql -d news -f newsdata.sql```: psql commands to connect the database and to run the sql statements

The Three Tables included in the Database are:
__Authors table__
__Articles table__
__Log table__

The queries are written for this questions:
1. What are the most popular three articles of all time?
2. Who are the most popular article authors of all time?
3. On which days did more than 1% of requests lead to errors? 

* python code and query is written and saved as loganalysis.py
## Execution Of the Program:
1.python3 loganalysis.py : To get the output of popular articles,popular authors and error days.

