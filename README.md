# Logs Analysis
This is the third project for the Udacity Full Stack Nanodegree.

## To Run

### You will need:
- Python3
- Vagrant
- VirtualBox
- newsdata.sql

### To Run

Launch Vagrant VM by running `vagrant up`, you can the log in with `vagrant ssh`

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.

The database includes three tables:
- Authors table
- Articles table
- Log table

To execute the program, run `python3 newsdata.py` from the command line.