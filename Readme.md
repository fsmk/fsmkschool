FSMK School
==========

Platform for managing sessions/workshops conducted in FSMK GLUGS


Requirements
------------

* PostgreSQL
* Python 2.7
* virtualenv

How to setup
------------

* Clone the repo

        git clone https://github.com/fsmk/fsmkschool.git
        cd fsmkschool

* setup virtualenv and install python packages

        virtualenv .
        . bin/activate
        pip install -r requirements.txt

* create a database

        createdb pythonexpress

* add schema 
        
        psql pythonexpress < broadgauge/schema.sql

* run the app

        python run.py
