# Logs Analysis Project
This project's goal is to build an internal reporting tool that will use infromation from a database to discover what kind of articles the site's readers like.

## Python Script
The python script `solution.py` analyzes the news data base and answers the three following questions:

1. What are the most popular three articles of all time?
1. Who are the most popular article authors of all time?
1. On which days did more than 1% of requests lead to errors?

## Usage
Prerequisites: VirtualBox, Vagrant
1. Obtain the VM by cloning the Udacity repo: https://github.com/udacity/fullstack-nanodegree-vm
1. Bring up the VM - `cd vagrant` and `vagrant up`
1. From within the vm, download and unzip the [Postgres newsdata](https://d17h27t6h515a5.cloudfront.net/topher/2016/August/57b5f748_newsdata/newsdata.zip)
1. Load the data - `psql -d news -f newsdata.sql`
1. From within the vm, download the `solution.py` script
1. Run the script to generate the log report - `python3 solution.py`
1. A copy of the intended output is located in `solution_output.txt`
